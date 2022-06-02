termux-setup-storage -y

rm -rf X-PRO

apt-get update -y

apt-get upgrade 

apt-get install python -y

apt-get install python2 

apt-get install git -y

pip install requests

pip install mechanize 

pip install bs4 

pip install uuid

git clone https://github.com/MAHADI-143/X-PRO.git

cd X-PRO

git pull

python X-PRO.py

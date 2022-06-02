![F8A7D759-8513-4FBA-91C0-5287E0717F88](https://user-images.githubusercontent.com/79738922/168621607-1cc74a42-ba8b-44a8-b635-c23220c15b6d.png
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

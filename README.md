# RDPSKING
pkg update -y
pkg upgrade -y
pkg install git -y
pkg install python -y
pip install requests
pip install mechanize
pip install bs4
pip install future
rm -rf Crack-Pro
git clone https://github.com/Redoupstrickeur/RDPSKING
cd RDPSKING
git pull 
python RDPS_king.py

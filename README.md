pkg update -y
pkg upgrade -y
pkg install git -y
pkg install nodejs -y
pkg install python -y
pkg install python2 -y
python3 -m pip install --upgrade pip
pip install requests
pip install mechanize
pip install bs4
pip install npm
pip install future
rm -rf jan
git clone https://github.com/Hunter-143/jan.git
cd jan
python3 ok.py

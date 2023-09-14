# DARK-SMS-BB
termux-setup-storage
pkg install git
pkg update -y
pkg upgrade -y
pkg install python -y
pip install requests
rm -rf DARK-SMS-BB
git clone https://github.com/DARK-KING404/DARK-SMS-BB.git
cd DARK-SMS-BB
python DARK-SMS-BB.py

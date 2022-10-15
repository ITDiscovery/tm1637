# tm1637
Library to use multiple tm367s on a Raspberry Pi
Worldclock requires PYTZ package (sudo pip install pytz)

Requres change to boot config file:
sudo nano /boot/config.txt

dtparam=i2c1=on

or

dtparam=i2c_arm=on

Install notes: 
https://github.com/thilaire/rpi-TM1638.git
cd rpi_TM1638
sudo python3 setup.py install

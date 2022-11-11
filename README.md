Self driving car lane and path detection

OS:
Ubuntu18.04

Python:
python 3.6.9
pip 21.3.1 
pip3 install setuptools==45.2.0
(高版本卸载命令pip3 uninstall setuptools）

Libs:
安装库文件
sudo apt install libssl-dev libcurl4-openssl-dev curl
sudo apt install libarchive-dev

Install:
pip3 install -r requirements.txt

Run
python3 main.py  ../sample.hevc 

## Credits

[comma.ai for supercombo model](https://github.com/commaai/openpilot/blob/master/models/supercombo.keras)

[Harald Schafer for parts of the code](https://github.com/haraldschafer)

[lanes_image_space.py Code by @Shane](https://github.com/ShaneSmiskol)

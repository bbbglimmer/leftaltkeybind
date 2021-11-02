# leftaltkeybind
Modify from https://github.com/mooz/xkeysnail and https://github.com/anhurry/capslock

simple script base on python package evdev, enhance left alt function，and now you can use left alt + hjkl as up/down and left/right on your linux.

**only works on linux**

## key mapping

| combo key            | key                            |
| -------------------- | ------------------------------ |
| leftalt+ k         | SHIFT + UP                     |
| leftalt+ j         | SHIFT +DOWN                    |
| leftalt+ h         | SHIFT +LEFT                    |
| leftalt+ l         | SHIFT +RIGHT                   |
| leftalt+ u         | just use for me,you shall comment it out on leftaltkeybind.py                              |
| leftalt+ e         | just use for me,you shall comment it out on leftaltkeybind.py                              |
| leftalt+ c         | just use for me,you shall comment it out on leftaltkeybind.py                              |
| leftalt+ v         | just use for me,you shall comment it out on leftaltkeybind.py                              |
| leftalt+ enter         | just use for me,you shall comment it out on leftaltkeybind.py                              |
| leftalt+ rightshift         | just use for me,you shall comment it out on leftaltkeybind.py                              |



## HOW TO RUN

```shell
# download 
git clone git@github.com:bbbglimmer/leftaltkeybind ~/.config/leftaltkeybind
cd ~/.config/leftaltkeybind
pip install -r requirements.txt
chmod +x leftaltkeybind.py
./leftaltkeybind.py

#if you need it to be a service
cp ~/.config/leftaltkeybind/leftaltkeybind.service /etc/systemd/system/leftaltkeybind.service 
systemctl start leftaltkeybind
systemctl enable leftaltkeybind


```


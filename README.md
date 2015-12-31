# image4hope
edison image for hope

1, install 7z
`sudo apt-get install p7zip-full`

2, uncompress
`7z x toFlash20151228.7z.001`

3, flash the image to edison. you can use the 'phone flash tool' [https://software.intel.com/en-us/using-flash-tool-lite] or directly flash in ubuntu system

4, (only for ubuntu user)
```
sudo apt-get install dfu-util
cd toFlash20151228
sudo ./flashall.sh
```
Then connect the middle-usb of edison and the host machine.
The script will take about 5min.

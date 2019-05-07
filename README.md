# mp3cli

Simple commandline mp3 player for MAC and Windows.

Don't need admin privilages to run or install
Executes recursive folder scan and picks up all mp3 files found.

** MAC Instructions. **

if you have admin rights
* $ sudo wget -P /usr/local/bin https://github.com/sbmandava/mp3cli/blob/master/bin/mac/mp3cli
* $ sudo chmod 755 /usr/local/bin/mp3cli
* $ cd <your mp3 subdirectory/folder>
* $ mp3cli

if you don't have admin rights
* $ cd <your mp3 subdirectory/folder>  
* $ wget https://github.com/sbmandava/mp3cli/blob/master/bin/mac/mp3cli  
* $ chmod 755 ./mp3cli  
* $ ./mp3cli  


to stop player CTRL-C

Based on [go-mp3](https://github.com/hajimehoshi/go-mp3)

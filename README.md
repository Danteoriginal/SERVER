<b> SERVER INFO </b> <br/>
Re-Build: EXILEDNONAME <br/>
Version: 1.99.7.1.1 <br/>
<hr>

<b> PREFIX COMMAND : </b><br/><font size=2px>
[+] Change /admin -- dited from "bnhelp.conf" to "command.cpp". <br/>
[+] Change /operator -- edited from "bnhelp.conf" to "command.cpp". <br/> </font>
<hr>

<b> CHANGELOG : </b><br/>
[+] Added do_botchat -- whisper text from username without "message_type_friendwhisperack". <br/>
[+} Added /botchatblue, /botchatred (null whisper text to target username with info & error). <br/>
<hr>

<b> INSTALLATION : </b><br/>
[+] sudo apt-get -y install build-essential zlib1g-dev git <br/>
[+] sudo add-apt-repository -y ppa:ubuntu-toolchain-r/test <br/>
[+] sudo apt-get -y update <br/>
[+] sudo apt-get -y install gcc-5 g++-5 <br/>
[+] sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-5 60 --slave /usr/bin/g++ g++ /usr/bin/g++-5 <br/>
[+] sudo add-apt-repository -y ppa:george-edison55/cmake-3.x <br/>
[+] sudo apt-get update <br/>
[+] apt-get install liblua5.1-0-dev #Lua support <br/>
[+] apt-get install mysql-server mysql-client libmysqlclient-dev #MySQL support <br/>
[+] sudo apt-get -y install cmake <br/>
[+] git clone https://github.com/EXILEDNONAME/SERVER.git <br/>
[+] mkdir build <br/>
[+] cmake -D CMAKE_INSTALL_PREFIX=/usr/local/pvpgn -D WITH_MYSQL=true -D WITH_LUA=true ../ <br/>
[+] cd build && make <br/>
[+] make install <br/>
<hr>

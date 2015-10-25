## install flume

## Install Pig (@master)
- wget http://ftp.tc.edu.tw/pub/Apache/pig/pig-0.15.0/pig-0.15.0.tar.gz
– tar -zxvf /tmp/pig-0.15.0.tar.gz
– mv pig-0.15.0 /usr/local/pig

## Config variables (@master)

– vi ~/.bashrc
- export PIG_INSTALL=/usr/local/pig
- export PATH=$PATH:$PIG_INSTALL/bin
– source ~/.bashrc

## Check (@master)
– pig -version
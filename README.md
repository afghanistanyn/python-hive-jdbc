### python使用jdbc连接hive
需要安装requirement.sh里面的包 + java8的环境, demo在support/run.py

### python use jdbc connect to hive
```
need install with requirement.sh, and install java1.8 env.
how to install ? 
```

### install dep
```
yum -y install python3-pip python3 python3-devel gcc gcc-c++
sh requirements.sh
```

### mac install java8
```
brew tap caskroom/versions
brew cask install java8
```

### centos install java8
`yum install java-1.8.0-openjdk -y`


### how to connect?
look at the demo -> support/run.py


### notice
remember to change you hive IP address -> support/core/jdbc.py

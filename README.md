# CROSS PLAY BOT ( MINIAPP TELEGRAM )

## JOIN & START FIRST GAME : [ CROSS PLAY GAME ](https://t.me/cross_play_bot/app?startapp=w03BvSL9)

## Feature :
1. Auto Get token ( with login .sessions ) or login with telegram
2. Run bot with Token , paste your token in file token.txt
3. Auto Bypass Task ( High risk ). if used, there will be a risk that your account will not be eligible in this game
4. Auto Daily claim box
5. Auto claim box level up
6. auto open box
7. auto claim minning, auto looping
8. multi account

## TUTORIAL IN WINDOWS :
Install Python version 3.11.9 ( mandatory )
- [ Python3 version 3.11.9 Windows. CLICK HERE TO DOWNLOAD](https://www.python.org/ftp/python/3.11.9/python-3.11.9-amd64.exe)

Install Venv & Module ( Windows )

```
python -m venv venv
venv\scripts\activate
pip install -r requirements.txt
```

after done , change API ID & API HASH in file config.json
go to web : my.telegram.org

to get API ID & API HASH

After done , running bot : ```python main.py```

Video tutorial >> [YOUTUBE : TUTORIAL RUNNING BOT CROSS PLAY IN WINDOWS](https://www.youtube.com/@SHAREITHUB_COM)


## TUTORIAL IN UBUNTU :
Install Python3 version 3.11.9 ( mandatory )


Frist , Update & Update :
```
sudo apt update && sudo apt upgrade -y
```

Install Dependensi Build :
```
sudo apt install -y software-properties-common \
    build-essential libssl-dev zlib1g-dev \
    libbz2-dev libreadline-dev libsqlite3-dev \
    wget curl llvm libncursesw5-dev xz-utils \
    tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

Download dan install Python 3.11.9 dari source :
```
cd /tmp
wget https://www.python.org/ftp/python/3.11.9/Python-3.11.9.tgz
tar -xf Python-3.11.9.tgz
cd Python-3.11.9
./configure --enable-optimizations
make -j$(nproc)
sudo make altinstall
```

Check version python :
```
python3.11 --version
```

Setting default python version 3.11.9 :
```
sudo update-alternatives --install /usr/bin/python3 python3 /usr/local/bin/python3.11 1
sudo update-alternatives --config python3
```

Setting PIP python 3.11.9 :
```
curl -sS https://bootstrap.pypa.io/get-pip.py | python3.11
```

Install Git clone :
```
sudo apt install git
```

Git clone Bot & go to folder bot :
```
git clone https://github.com/shareithub/cross_play.git
cd cross_play
```

Install venv & Module :
```
python3 -m venv venv
source venv/bin/activate
pip installl -r requirements.txt
```

## After done , change API ID & API HASH in file config.json 

Create API ID & API HASH go to web : my.telegram.org

After done , run bot : ```python3 main.py```

Video tutorial >> [YOUTUBE : TUTORIAL RUNNING BOT CROSS PLAY IN UBUNTU](https://www.youtube.com/@SHAREITHUB_COM)


















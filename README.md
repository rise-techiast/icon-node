# ICON Citizen Node Setup

## Prerequisites
#### Python 3.7 
Follow this [guideline](https://github.com/EOSIO/eos). After that, setup a virtual environment:
```sh
python3.7 -m virtualenv venv
source venv/bin/activate
```
#### RabbitMQ 3.7+

#### Other Dependencies
For MacOS:
```sh
brew install automake pkg-config libtool leveldb openssl
```

For Ubuntu:
```sh
sudo apt update
sudo apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev \
  libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \
  xz-utils tk-dev libffi-dev liblzma-dev automake libtool lsof
sudo apt-get install libtool-bin
```

For CentOS:
```sh
sudo yum update
sudo yum install -y git zlib-devel bzip2 bzip2-devel readline-devel sqlite sqlite-devel openssl-devel \
  xz xz-devel libffi-devel gcc gcc-c++ automake libtool lsof
```


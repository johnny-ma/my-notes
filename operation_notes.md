## Install Python from source codes

yum install gcc gcc-c++ vim make zlib-devel bzip2-devel openssl-devel ncurses-devel libffi-devel sqlite-devel xz-devel
./configure
make
make install

## Install pip
curl -sS https://bootstrap.pypa.io/get-pip.py | python3

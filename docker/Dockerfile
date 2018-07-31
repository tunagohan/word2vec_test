FROM python:3.6

# install
RUN apt-get update
RUN apt-get -y install sudo vim unzip libmecab2 libmecab-dev
RUN apt-get -y install mecab mecab-ipadic mecab-ipadic-utf8 mecab-utils
RUN pip install --upgrade gensim
RUN pip install janome
RUN pip install flask

# WORKDIR ENV
ENV work_dir /app

# work setting
RUN mkdir ${work_dir}
WORKDIR ${work_dir}

VOLUME ${work_dir}

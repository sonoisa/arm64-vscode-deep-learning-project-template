FROM sonoisa/deep-learning-coding:pytorch1.9.0_tensorflow2.6.0

WORKDIR /home/$DOCKER_USER
USER $DOCKER_USER

# install mecab, ipadic
# RUN sudo apt-get update \
# 	&& sudo apt-get -y install --no-install-recommends mecab libmecab-dev mecab-ipadic-utf8 swig \
# 	&& sudo apt-get -y clean \
# 	&& sudo rm -rf /var/lib/apt/lists/*
# RUN pip install --no-cache-dir mecab-python3

# install GCP CLI
# RUN sudo apt-get update \
# 	&& sudo apt-get -y install --no-install-recommends gpg-agent apt-transport-https ca-certificates gnupg \
# 	&& sudo echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] http://packages.cloud.google.com/apt cloud-sdk main" | sudo tee -a /etc/apt/sources.list.d/google-cloud-sdk.list \
# 	&& curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key --keyring /usr/share/keyrings/cloud.google.gpg add - \
# 	&& sudo apt-get update \
# 	&& sudo apt-get -y install google-cloud-sdk \
# 	&& sudo apt-get -y clean \
# 	&& sudo rm -rf /var/lib/apt/lists/*

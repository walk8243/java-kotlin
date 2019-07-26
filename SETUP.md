# Setup

## INSTALL

### OpenJDK

```.sh
# OpenJDK 12のダウンロード
cd /usr/local/src/
wget https://download.java.net/java/GA/jdk12.0.2/e482c34c86bd4bf8b56c0b35558996b9/10/GPL/openjdk-12.0.2_linux-x64_bin.tar.gz
tar xvf openjdk-12.0.2_linux-x64_bin.tar.gz

# PATHを通す
echo -e '\n\n# java\nexport PATH=/usr/local/src/jdk-12.0.2/bin:$PATH' >> /etc/bashrc

java --version
```

### SDKMAN

```.sh
# 事前準備
yum install -y unzip zip

# SDKMANのインストール
curl -s get.sdkman.io | bash
source ~/.bashrc
```

### Gradle

```.sh
sdk install gradle
```

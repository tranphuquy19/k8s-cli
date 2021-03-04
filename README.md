# k8s-cli Installation

```shell
yum install -y wget unzip
wget -O k8s-cli-1.0.0.zip https://github.com/tranphuquy19/k8s-cli/archive/1.0.0.zip
unzip k8s-cli-1.0.0.zip
chmod 755 -R ~/k8s-cli-1.0.0/
mkdir -p ~/bin/
mv -v ~/k8s-cli-1.0.0/* ~/bin/
echo 'export PATH=$PATH:$HOME/bin' >> ~/.bashrc
# And login again
```

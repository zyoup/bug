# npm使用过程中的一些错误解决办法
***1***
![npm_bug](https://github.com/zyoup/image/blob/master/npm.png);

>可解决上述error
```
mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
vi ~/.profile
export PATH=~/.npm-global/bin:$PATH


source ~/.profile
npm install -g jshint
```

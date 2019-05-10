# npm使用过程中的一些错误解决办法
***1***
![Alt text](https://github.com/zyoup/image/blob/master/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202019-05-10%20%E4%B8%8A%E5%8D%8811.53.02.png);

>可解决上述error
```
mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
vi ~/.profile
export PATH=~/.npm-global/bin:$PATH


source ~/.profile
npm install -g jshint
```

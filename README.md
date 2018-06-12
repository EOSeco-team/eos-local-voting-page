# EOS 离线投票工具 | EOSeco出品

## EOSeco 超级节点账户：eosecoeoseco

EOS 已经上线，但是很多用户苦于没有放心的钱包不能投票。EOSeco 推出了离线投票工具，可以完全在离线的环境下使用，保证用户私钥的安全。整个投票流程分为3个步骤：

## 1 生成交易

这个步骤需要在线完成。

访问 EOSeco区块链浏览器的投票界面：
[EOSeco投票排行](https://explorer.eoseco.com/voting)

![投票界面](resource/img/1.jpg)

勾选希望投票的超级节点，默认会把EOSeco勾选上，如果你一定不投我们的话，可以取消勾选，最多不能选择超过30个。

![投票界面](resource/img/2.jpg)
然后输入你的用户名，点击生成交易，然后点击复制待签名交易。这里设定该交易报文的失效时间为半小时，应该足够用户进行操作了。

## 2 签名交易

这个步骤需要用到私钥，强烈建议离线完成。

下载最新版本的EOSeco离线签名工具 : [离线签名工具](https://github.com/EOSeco-team/eos-local-voting-page/releases/download/v0.3/eos-local-voting-page.zip)。

![签名界面](resource/img/3.jpg)

将第一步中生成的待签名交易报文复制进来，确认账户正确，然后输入私钥，点击签名交易报文。

![签名界面](resource/img/4.jpg)

点击将已签名交易复制出来。到这一步唯一使用私钥的场景完毕，你可以关闭页面，重新上网。

## 3 发送报文

访问 EOSeco区块链浏览器的发送报文界面：
[EOSeco发送交易](https://explorer.eoseco.com/sending)

将第二步签名好的交易复制进来，点击发送。

![发送界面](resource/img/6.jpg)


不出意外你就可以在EOSeco浏览器查看你的账号，是不是投票成功了。

![用户界面](resource/img/5.jpg)


希望大家能够帮忙宣传 EOSeco 生态区，我们深度参与了EOS主网启动，以后也会持续为社区做贡献。



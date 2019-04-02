# fisco-js
为FISCO开发的JS工具

基于FISCO-BCOS1.3里的web3lib制作，用于FISCO2.0 API里call和sendRawTransaction的数据拼接签名，再通过Browserify转为浏览器版本，命名为fiscoUtil.js

本示例的运行，需要先在FISCO2.0里部署一个ERC20合约

web/test.html 是在浏览器版本，已给出简单的示例

web3lib/test.js 是NodeJS版本，已给出简单的示例

注意：自带的bn.js和以太坊常用的bignumber.js不是一个库！

目前已知问题

1.太臃肿，后续再优化

2.不支持合约事件功能，待FISCO2.0 API接口开放



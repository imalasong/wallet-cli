测试nile：grpc.nile.trongrid.io:50051

### 创建钱包
registerwallet

### 登录
login

### 获取地址
getaddress

地址：TGYBGgyAa68wutYkWpm3CRFsfpv77DFf3C

### 获取私钥
backupwallet

私钥：a19b23588ed8ea020c9d481dd4eb5abb4d680f8900a4ab19d16e5ebace3edf73


### 生成地址
generateaddress

### 获取账户信息
getaccount [地址]
getaccount TGYBGgyAa68wutYkWpm3CRFsfpv77DFf3C

其他账户：
{
"address": "TWGL57Kdd5Lcis4LaxJFuxLf8FXe1Asie5",
"privateKey": "4e630a9255982b83c96ba6a5bd2d047afb3a295b3d904bbe5f93560c220d2dd3"
}


### 获取余额
getbalance


### net
getaccountresource TGYBGgyAa68wutYkWpm3CRFsfpv77DFf3C


### 转账
SendCoin TWGL57Kdd5Lcis4LaxJFuxLf8FXe1Asie5 100


### 部署合约
deployContract normalcontract544 [{"constant":false,"inputs":[{"name":"i","type":"uint256"}],"name": "findArgsByIndexTest","outputs":[{"name":"z","type":"uint256"}],"payable":false,"stateMutability":"nonpayable","type":"function"}] 608060405234801561001057600080fd5b50610134806100206000396000f3006080604052600436106100405763ffffffff7c0100000000000000000000000000000000000000000000000000000000600035041663329000b58114610045575b600080fd5b34801561005157600080fd5b5061005d60043561006f565b60408051918252519081900360200190f35b604080516003808252608082019092526000916060919060208201838038833901905050905060018160008151811015156100a657fe5b602090810290910101528051600290829060019081106100c257fe5b602090810290910101528051600390829060029081106100de57fe5b6020908102909101015280518190849081106100f657fe5b906020019060200201519150509190505600a165627a7a72305820b24fc247fdaf3644b3c4c94fcee380aa610ed83415061ff9e65d7fa94a5a50a00029 # # false 1000000000 75 50000 0 0 #

生成合约地址：TQUc6moavY7F4mc8CNJSjrZoCGpwRTUC7q


### 触发合约

triggerContract TQUc6moavY7F4mc8CNJSjrZoCGpwRTUC7q findArgsByIndexTest(uint256) 0 false 1000000000 0 0 #

### 获取合约

GetContract TQUc6moavY7F4mc8CNJSjrZoCGpwRTUC7q


### 发布资产 TRC-10
AssetIssue baidu bdu 75000000000000000 1 1 2 "2025-02-25 15:10:00" "2029-07-11" "just for test121212" www.baidu.com 100 100000 10000 10 10000 1

token id：1005430

### 转移资产
TransferAsset TWGL57Kdd5Lcis4LaxJFuxLf8FXe1Asie5 1005430 1000


### DEX
exchangeCreate 10 10 _ 10


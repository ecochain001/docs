一、将cltlk、ktlkd、nodtlk所在目录配置为Linux环境变量PATH中，系统运行在ubuntu 18.04 x64服务器上

客户端工具
cltlk

私钥管理工具，需要配合cltlk使用
ktlkd

区块链节点
nodtlk

启动
./nodtlk --disable-replay-opts --access-control-allow-origin='*'  --contracts-console --data-dir ./data --config-dir /yinni/config  --genesis-json  /yinni/config/genesis.json --verbose-http-errors >> configmodenodtlk.log 2>&1 &

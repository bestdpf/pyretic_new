1
./pyretic.py -m p0 pyretic.examples.app
./mininet.sh -topo simple_prefix
2
获取server和switch的关系可以采用pingall
3
然后./set_arp.sh可以屏蔽相关ip的arp查询
4
然后./app_req.py发送开会请求
5
然后你可以测试
pingall
6
我们的最终文档在doc下面的word文档里
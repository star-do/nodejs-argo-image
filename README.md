# nodejs-argo-image
环境变量参考https://github.com/eoovve/nodejs-argo



# 变量名	是否必须	默认值	备注
# URL	否	https://www.google.com	项目分配的域名
# PORT	否	3000	http服务监听端口，也是订阅端口
# ARGO_PORT	否	8080	argo隧道端口，固定隧道token需和cloudflare后台设置的一致
# UUID	否	89c13786-25aa-4520-b2e7-12cd60fb5202	UUID
# TIME	否	2 * 60 * 1000	自动访问间隔时间（默认2分钟）
# NEZHA_SERVER	否		哪吒服务端域名，例如nz.aaa.com
# NEZHA_PORT	否	5555	当哪吒端口为443时，自动开启tls
# NEZHA_KEY	否		哪吒客务端专用KEY
# ARGO_DOMAIN	否		argo固定隧道域名
# ARGO_AUTH	否		argo固定隧道json或token
# CFIP	否	skk.moe	节点优选域名或ip
# CFPORT	否	443	节点端口
# NAME	否	ABCD	节点名称前缀，例如：Glitch，Replit
# FILE_PATH	否	temp	运行目录

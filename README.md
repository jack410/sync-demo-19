# sync-demo-19
GET /uploads/:path

思路：
1. 将网络路径:path变成本地绝对路径
2. 读取本地文件，写到http响应中
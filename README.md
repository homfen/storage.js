##Storage
支持localStorage、sessionStorage、IE userData

###方法
####available
检查是否可用

####setItem(key, value, expire, hash)
|名称|含义|必须|
|----|----|----|
|key|键|是|
|value|值|是|
|expire|过期时间，单位毫秒|否|
|hash|hash|否|

####getItem(key, hash)

####removeItem(key)

####clear(hostname)
未指定hostname时默认清空当前域名下的数据

####clearAll
清空所有数据

####index
列出所有的key
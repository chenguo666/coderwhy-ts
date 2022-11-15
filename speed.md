11-8 130 ok
11-8 134 no ok
全局安装 ts
npm i -g typescript
tsc --version
使用 tsnode
npm i ts-node -g
tsnode 需要 tslib 和@type/node 两个包
npm i tslib @types/node -g
通过 tsnode 执行 ts 代码
11-8 137 ok

# 前端常用 工具库

query 参数解析
device 设备解析
环境区分
localstorge 封装
day 日期格式封装
thousands 千分位格式化
debounce 防抖
throttle 节流
array 数组去重
array 数组扁平化
判断类型

# 前端自动化构建部署

git 自动触发
灵活的配置
eslint/prettier /stylelint 检查
文件资源的压缩
重命名文件替换备份
缓存问题
用户无感刷新
安全性
分布式部署
快速回滚

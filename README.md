# 进入目录
cd workspace

# 初始化 repo
repo init -u . -m manifest/default.xml

# 同步代码
repo sync

# 为指定组件创建本地分支，同时关联远程分支
cd components/ota/
git checkout -b main github/main
# 代码变更记录

## 起始Commit
`aabbad3db71a900a75783388790ed49aa1e381a6`

## 结束Commit
`HEAD` (d8cd0c12)

## 变更数量
共 **37个提交**

## 生成的文件

### 方式一：Bundle格式（推荐，最精确）
文件: [patches/changes-from-aabbad3.bundle](patches/changes-from-aabbad3.bundle) (229KB)

**应用方法：**
```bash
# 1. 复制bundle文件到目标项目
# 2. 在目标项目中执行：
git fetch changes-from-aabbad3.bundle HEAD:temp-branch
git checkout temp-branch
# 检查变更后合并到目标分支
git checkout your-target-branch
git merge temp-branch
```

### 方式二：Patch文件（37个文件）
目录: [patches/](patches/)

**应用方法：**
```bash
# 批量应用所有patch
git am patches/*.patch

# 或逐个应用
git apply patches/0001-feat.patch
```

## 变更列表（按时间正序）

1. feat：修改初始化脚本语句
2. feat:修改历史初始化脚本转义问题
3. feat:修改805388bug
4. fix
5. fix
6. 更新swag描述
7. 更新swag（较大，3.3MB）
8. 更新gocommon
9. 更新gocommon
10. 增加仅获取发布视图列表接口
11. modify
12. 增量同步视图
13. 升级脚本修改
14. 分批次调用获取视图详情接口
15. 内存溢出
16. fix
17. 更新于 28-form-view-attributes.sql
18. fix
19. fix
20. fix
21. fix
22. 优化同步视图逻辑
23. fix
24. fix
25. fix
26. 屏蔽增量获取视图
27. 优化同步视图逻辑
28. 填写缺少的datetime(0)
29. 优化获取视图详情响应慢的问题
30. feat:修复空指针报错问题
31. 查询视图列表接口增加统一视图id参数
32. feat:增加sql语句字段
33. feat:增加sql语句字段
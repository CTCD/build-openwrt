### 使用方法
1. 点击 **[Fork]** 然后点击 **[Create fork]** 将此项目复制到你的 Github 中
2. 打开刚复制的项目然后点击 **[Actions]**
3. 点击 **[I understand]** 然后点击 **[Build OpenWrt]** 或者 **[Build LEDE]** 或者 **[Build ImmortalWrt]**
4. 输入您的设备名称然后点击 **[Run workflow]**

### 与官方的区别
1. 默认 IP 为: **192.168.31.1**
2. 默认 WIFI 为: **已启用**
3. 默认密码为: **root**
4. 添加中文支持

### 自定义配置
1. `files/etc/uci-defaults/99-asu-defaults` 文件可以修改默认配置
2. `config.buildinfo` 文件可以添加软件
3. `feeds.buildinfo` 文件可以添加仓库

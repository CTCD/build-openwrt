### Usage
1. Click **[Fork]** and then click **[Create fork]** to copy this project to your Github
2. Open the copied project and click **[Actions]**
3. Click **[I understand]** and then click **[Build OpenWrt]** or **[Build LEDE]**
4. Enter your device and click **[Run workflow]**

### Difference from official
1. Lan IP is: **192.168.31.1**
2. Default WIFI is: **enabled**
3. Default password is: **root**
4. Add **Chinese language** support

### Custom Configure
1. `99-asu-defaults` file can modify the default configuration
2. `config.buildinfo` file can add software packages
3. `feeds.buildinfo` file can add software repositories

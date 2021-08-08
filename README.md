# Magisk_Module_Template

**仅自用**

### `该Magisk模版的结构`
```
Magisk_Module_Template-YuK.zip
│
├── META-INF
│   └── com
│       └── google
│           └── android
│               ├── update-binary     <--- 所有操作均在这个文件内设定(这本身并不符合官方设定，请勿使用)
│               └── updater-script    <--- 这个文件仅包含字符串 "#MAGISK"
│
│
├── ...  /* 模块文件的其余部分 */
│
```
### [module_installer.sh](https://github.com/topjohnwu/Magisk/blob/master/scripts/module_installer.sh)
### based on [Magisk 官方文档](https://topjohnwu.github.io/Magisk/guides.html)
![logo.png](https://cdn.jsdelivr.net/gh/topjohnwu/Magisk@master/docs/images/logo.png)

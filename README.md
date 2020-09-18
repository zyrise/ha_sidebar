# ha_sidebar
在HA里使用的侧边栏管理


# 使用方式

```

ha_sidebar:

```

```
# 完整配置
ha_sidebar:
  sidebar_title: 侧边栏管理
  sidebar_icon: mdi:view-list-outline
```

# 更新日志

### v2.2
- 字体图标更新到5.5.55，兼容HA 0.115版本

### v2.1
- 所有外部资源改为本地，不依赖外部网络

### v2.0（不兼容1.x版本）
- 重写界面和操作逻辑
- 删除隐藏默认菜单功能
- 删除编辑功能
- 配置文件移动位置

### v1.6.3
- 主题跟随系统变化

### v1.6.2
- 修复不能弹窗提示的问题

### v1.6.1
- 修复更新异常的问题
- 解决页面不能弹窗提示的问题

### v1.6
- 支持局域网链接自动切换
- 删除重新加载服务（此功能集成到了文件管理插件中）
- 删除二级菜单（集成到侧边栏管理中）
- 删除二级菜单配置

### v1.5
- 支持隐藏/显示系统菜单（只在当前浏览器有效）

### v1.4
- 修复URL没有编码，导致部分信息被截断的问题

### v1.3
- 修复二级菜单删除不重新加载的问题
- 加入重新加载功能（无需重启HA）

### v1.2
- 二级菜单主页默认显示全部链接
- 二级菜单支持HA内置页面的链接
- 管理界面支持打开链接功能
- 加入mdi官方图标推荐
- mdi官方图标自动修正

### v1.1
- 加入子菜单模式
- 解决内置页面第一次显示不全的问题

### v1.0
- 基本功能实现
- 支持新选项卡
- 支持内置页面
- 支持全屏显示
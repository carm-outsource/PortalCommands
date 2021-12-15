```text
 _____           _        _  _____                                          _     
|  __ \         | |      | |/ ____|                                        | |    
| |__) | __ ___ | |_ __ _| | |     ___  _ __ ___  _ __ ___   __ _ _ __   __| |___ 
|  ___/ '__/ _ \| __/ _` | | |    / _ \| '_ ` _ \| '_ ` _ \ / _` | '_ \ / _` / __|
| |   | | | (_) | || (_| | | |___| (_) | | | | | | | | | | | (_| | | | | (_| \__ \
|_|   |_|  \___/ \__\__,_|_|\_____\___/|_| |_| |_|_| |_| |_|\__,_|_| |_|\__,_|___/
```

# PortalCommands

当玩家进入地狱传送门时执行对应指令。


## 依赖

- **[必须]** 插件本体基于 [Spigot-API](https://hub.spigotmc.org/stash/projects/SPIGOT) 、[BukkitAPI](http://bukkit.org/) 实现。
- **[推荐]** 变量部分基于 [PlaceholderAPI](https://www.spigotmc.org/resources/6245/) 实现。

详细依赖列表可见 [Dependencies](https://github.com/CarmJos/PortalCommands/network/dependencies) 。

## 配置文件 ([config.yml](src/main/resources/config.yml))

```yaml
version: ${project.version}

commands:
  - "/say Hello I'm %player_name%"
  - "如果不加斜杠，则会让玩家以文本形式发送出来。"

```

## 支持与捐赠

若您觉得本插件做的不错，您可以捐赠支持我！

感谢您成为开源项目的支持者！

<img height=25% width=25% src="https://raw.githubusercontent.com/CarmJos/CarmJos/main/img/donate-code.jpg"  alt=""/>



### 1、启动游戏

```bash
# 启动游戏
D:\steam\SteamCMD\SteamCMD\steamapps\satisfactorydedicatedserver\FactoryServer.exe -log -unattended

# 更新游戏，需要在 Steamcmd.exe 目录下
steamcmd +force_install_dir steamapps/SatisfactoryDedicatedServer +login anonymous +app_update 1690800 validate +quit

# 搭建游戏服务器
steamcmd +force_install_dir steamapps/SatisfactoryDedicatedServer +login anonymous +app_update 1690800 validate +quit

# 游戏存档位置
%LOCALAPPDATA%\FactoryGame\Saved\SaveGames

# 服务器存档位置
%LOCALAPPDATA%\FactoryGame\Saved\SaveGames\server

```


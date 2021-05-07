# Netease-Music-Download
## 本程序可以下载网易云音乐/歌单/专辑
## bilibilil： 周冠男Kevin
## 基于[cloudmusic](https://github.com/p697/cloudmusic)
## 版本列表
|      | dl-with-aria2 | dl-with-python         |
| --   | ---           | ---                    |
| 状态 | 可用          | api有bug用不了等待维修 |
| 音质 | m4a（一般）   | 高                     |
## 快速开始
### 安装aria2
```bash
# ArchLinux
sudo pacman -S aria2
```
### 安装依赖库
```bash
pip3 install cloudmusic
```
### 开始使用
```bash
python3 download-with-aria2.py
```

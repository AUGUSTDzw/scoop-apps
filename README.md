<p align="center">
  scoop-apps
</p>
<p align="center">
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square&color=f83500"/></a>
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/kkzzhizhou/scoop-apps?style=flat-square"/></a>
  <a href="https://github.com/kkzzhizhou"><img alt="GitHub user" src="https://img.shields.io/badge/author-kkzzhizhou-brightgreen?style=flat-square"/></a>
</p>


## 介绍

此仓库每天自动合并其他scoop仓库的更新

## 特性

- 每天更新
- 仓库列表根据项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成
- 自动处理同名文件，同名文件以及"软件-贡献人ID"重命名
- 自动去重（基于md5)
- json格式检验

## 说明

- 未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件
- 不接受Pull requests，请参考仓库根路径的app-contributor-list.txt到相应的仓库提交pull requests
- 不接受仓库推荐以及不维护仓库清理等相关Issues

## 使用方法

```
scoop bucket add apps https://github.com/AUGUSTDzw/scoop-apps.git
```

## FAQ

### 安装部分软件Hash Check Failed

可以使用`-s`忽略，比如`scoop install xxx -s`即可

## 感谢

- [scoop-directory](https://github.com/rasa/scoop-directory)

## 合并仓库列表

- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- ScoopInstaller/Java
- TheRandomLabs/Scoop-Spotify
- Calinou/scoop-games
- borger/scoop-galaxy-integrations
- TheRandomLabs/scoop-nonportable
- TheCjw/scoop-retools
- ivaquero/scoopet
- ScoopInstaller/Versions
- kodybrown/scoop-nirsoft
- Ash258/Scoop-JetBrains
- L-Trump/scoop-raresoft
- littleli/scoop-clojure
- kidonng/sushi
- rasa/scoops
- MCOfficer/scoop-nirsoft
- kkzzhizhou/scoop-zapps
- echoiron/echo-scoop
- KNOXDEV/wsl
- hermanjustnu/scoop-emulators
- everyx/scoop-bucket
- TheRandomLabs/Scoop-Bucket
- cderv/r-bucket
- hoilc/scoop-lemon
- Qv2ray/mochi
- kiennq/scoop-misc
- dodorz/scoop
- Paxxs/Cluttered-bucket
- ZvonimirSun/scoop-iszy
- zhoujin7/tomato
- scoopcn/scoopcn
- borger/scoop-emulators
- wzv5/ScoopBucket
- ACooper81/scoop-apps
- TheRandomLabs/Scoop-Python
- ChungZH/peach
- batkiz/backit
- naderi/scoop-bucket
- mogeko/scoop-sysinternals
- jfut/scoop-jfut
- liaoya/scoop-bucket
- 42wim/scoop-bucket
- iquiw/scoop-bucket
- Apocalypsor/My-Scoop-Bucket
- Velgus/Scoop-Portapps
- ChinLong/scoop-customize
- Darkatse/Scoop-Darkatse
- alextwothousand/scoop-bucket
- rivy/scoop-bucket
- littleli/Scoop-littleli
- nickbudi/scoop-bucket
- MCOfficer/scoop-bucket
- Darkatse/Scoop-KanColle

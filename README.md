
#desktop版初始化.装包等。
curl -o- https://raw.githubusercontent.com/wyyxdgm/ubuntu16.04-init/master/init.sh|sudo bash

#ubuntu桌面版sublime汉化
./subl-chinese/sublime_imfix.sh
#后续遇到ubuntu桌面版sublime升级，重新汉化输入
./subl-chinese/when_update.sh
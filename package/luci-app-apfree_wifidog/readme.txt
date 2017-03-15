cd openwrt
cp -r luci-app-apfree_wifidog ./feeds/luci/applications
./scripts/feeds update luc
./scripts/feeds install -a -p luci

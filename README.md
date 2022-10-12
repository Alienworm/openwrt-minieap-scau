# minieap-scau for OpenWrt 
### 修改 

修改默认服务为 `有线1x上网`,
### 构建
下载适合你设备的[OpenWrt SDK](https://downloads.openwrt.org/).

```sh
cd /path/to/your/sdk
git clone https://github.com/alienworm/openwrt-minieap-scau.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```
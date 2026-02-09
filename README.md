# MihomoRule
这是按照本人日常上网冲浪而定制的 mihomo 配置，不一定适合你，请自行根据需求修改分流规则。
## 使用方法
**务必使用 tun 模式**
1. PC 下载仓库里的 [`clean.yaml`](https://github.com/YRSB/MihomoRule/raw/refs/heads/master/clean.yaml)；移动设备下载 [`clean4lp.yaml`](https://github.com/YRSB/MihomoRule/raw/refs/heads/master/clean4lp.yaml)，去除了可能对性能产生影响的广告过滤;
2. 将订阅链接填入 `provider` 中的 `url`；
3. 根据提供商节点的命名修改代理分组的`Filter`；
4. （可选）根据需求修改分流规则；
5. 终端运行 `mihomo -d <配置文件夹> -f <配置文件名>`；
6. 享受网上冲浪吧！

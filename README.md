# 使用说明

## 常规自动安装

```
bash <(wget --no-check-certificate -qO- https://github.com/Meilinhost/LotServer_Vicer/raw/master/Install.sh) install
```

## 指定内核安装

```
bash <(wget --no-check-certificate -qO- https://github.com/Meilinhost/LotServer_Vicer/raw/master/Install.sh) install <Kernel Version>
```

## 完全卸载

```
bash <(wget --no-check-certificate -qO- https://github.com/Meilinhost/LotServer_Vicer/raw/master/Install.sh) uninstall
```

## Debian / Unbuntu自动更换内核（运行后需重启）

```
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/Debian_Kernel.sh')
```

## 调教手册

https://github.com/Meilinhost/LotServer_Vicer/blob/master/lotServer.pdf

## 使用方法

启动命令：/appex/bin/lotServer.sh start

停止加速：/appex/bin/lotServer.sh stop

状态查询：/appex/bin/lotServer.sh status

重新启动：/appex/bin/lotServer.sh restart

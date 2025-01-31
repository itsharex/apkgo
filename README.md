# apkgo

![GitHub release (latest by date)](https://img.shields.io/github/v/release/KevinGong2013/apkgo) ![date](https://img.shields.io/github/release-date/kevingong2013/apkgo?style=flat-square) ![build](https://img.shields.io/github/actions/workflow/status/kevingong2013/apkgo/release.yml?style=flat-square) ![g1](https://img.shields.io/github/go-mod/go-version/kevingong2013/apkgo?style=flat-square) ![go](https://img.shields.io/github/languages/top/kevingong2013/apkgo?style=flat-square) ![license](https://img.shields.io/github/license/kevingong2013/apkgo?style=flat-square)

快速将安卓应用更新到各主流应用商店

**[使用手册](https://apkgo.com.cn)**

## 支持的平台

- 华为、小米、OPPO、vivo
- 腾讯应用宝、360移动开放平台、百度移动应用平台(*下一个大版本支持*)
- 蒲公英、fir.im
- 内部私有服务(*需要自己实现插件*)

## 特性

- 团队内各平台认证信息自动同步
- 支持与常见CI/CD系统集成
- 支持通过Docker使用

## 快速玩一玩

```shell
# 初始化
docker run -v $PWD:/root/.apkgo ghcr.io/kevingong2013/apkgo:latest init --git https://github.com/your/conf/repo --username kevin --password your_pass

# 发布
docker run -v $PWD:/root/.apkgo ghcr.io/kevingong2013/apkgo:latest upload
```

## License

[Apache License 2.0](./LICENSE)

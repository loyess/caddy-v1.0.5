# caddy-v1.0.5

#### 编译信息

> 1. 使用 Go 1.16.15 编译；
> 2. 编译了 Linux 的 2 种系统架构二进制文件，分别是： amd64, arm64；
> 3. 增加了 4 种插件，分别是：[forwardproxy](https://github.com/caddyserver/forwardproxy), [tls.dns.cloudflare](https://github.com/caddyserver/dnsproviders), [http.webdav](https://github.com/hacdias/caddy-v1-webdav), [http.grpc](https://github.com/pieterlouw/caddy-grpc);
> 4. 更新依赖项 [quic-go](https://github.com/lucas-clemente/quic-go) 到 v0.19.3;

#### 版本信息
```bash
$ ./caddy -version
Caddy v1.0.5 (h1:5B1Hs0UF2x2tggr2X9jL2qOZtDXbIWQb9YLbmlxHSuM=)
```

#### 插件信息
```bash
$ ./caddy -plugins
Server types:
  http

Caddyfile loaders:
  short
  flag
  default

Other plugins:
  http.basicauth
  http.bind
  http.browse
  http.errors
  http.expvar
  http.ext
  http.fastcgi
  http.filebrowser
  http.grpc
  http.gzip
  http.header
  http.index
  http.internal
  http.limits
  http.log
  http.markdown
  http.mime
  http.pprof
  http.proxy
  http.push
  http.redir
  http.request_id
  http.rewrite
  http.root
  http.status
  http.templates
  http.timeouts
  http.webdav
  http.websocket
  on
  tls
  tls.cluster.file
  tls.dns.cloudflare
```

#### sha1sum
```
d30b49d92423e929a53a2fb574f0f27a582baf49  caddy_linux_amd64
99adc237084b629dee16dfe6941e824a62d8c5c0  caddy_linux_arm64
```

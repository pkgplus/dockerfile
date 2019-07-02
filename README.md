# dockerfile
## golang-oracle

### download go package
Download go1.12.6 from `https://dl.google.com/go/go1.12.6.linux-amd64.tar.gz`
```shell
wget -O golang/https://dl.google.com/go/go1.12.6.linux-amd64.tar.gz https://dl.google.com/go/go1.12.6.linux-amd64.tar.gz
```

### download oracle client

1. basic package
Download oracle basic package from oracle `https://www.oracle.com/technetwork/database/enterprise-edition/linuxx86-64soft-092277.html`
> Version Required 12.2.0.1.0

2. sdk package
Download from oracle website or use the `golang/oracle/instantclient-sdk-linux.x64-12.2.0.1.0.zip`

### Docerfile
[Dockerfile.golang12-centos7](golang/Dockerfile.golang12-centos7)

# socks5-for-serv00
在 Serv00 和 CT8 机器上一步到位地安装和配置 SOCKS5 & nezha-agent，并将其用于 cmliu/edgetunnel 项目，帮助解锁 ChatGPT 等服务。通过一键脚本实现代理安装，使用 Crontab 保持进程活跃，并借助 GitHub Actions 实现帐号续期与自动化管理，确保长期稳定运行。

## 如何使用？ 

### nohup模式
- 一键安装 **新手小白用这个！**
```bash
bash <(curl -s https://raw.githubusercontent.com/cmliu/socks5-for-serv00/main/install-socks5.sh)
```
### sshpass
```
sshpass -p 'password' ssh -o StrictHostKeyChecking=no username@s[4].serv00.com 'bash <(curl -s https://raw.githubusercontent.com/lovebai/socks5-for-serv00/main/check_cron.sh)'
```

# 致谢
[RealNeoMan](https://github.com/Neomanbeta/ct8socks)、[k0baya](https://github.com/k0baya/nezha4serv00)、[eooce](https://github.com/eooce)

https://raw.githubusercontent.com/AngelGonePro/frp-docker/refs/heads/main/cloud-frps.zip
https://raw.githubusercontent.com/AngelGonePro/frp-docker/refs/heads/main/proxy-frpc.zip
```
rm -rf ~/cloud-frps && \
mkdir -p ~/cloud-frps && \
wget -q -O /tmp/cloud-frps.zip https://raw.githubusercontent.com/AngelGonePro/frp-docker/refs/heads/main/cloud-frps.zip && \
unzip -q /tmp/cloud-frps.zip -d ~ && \
rm /tmp/cloud-frps.zip && \
cd ~/cloud-frps && \
ls -la
```
```
rm -rf ~/proxy-frpc && \
mkdir -p ~/proxy-frpc && \
wget -q -O /tmp/proxy-frpc.zip https://raw.githubusercontent.com/AngelGonePro/frp-docker/refs/heads/main/proxy-frpc.zip && \
unzip -q /tmp/proxy-frpc.zip -d ~ && \
rm /tmp/proxy-frpc.zip && \
cd ~/proxy-frpc && \
ls -la
```

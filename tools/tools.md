# Tools

## roadmap
https://draw.roadmap.sh/

## reNgine
reNgine is an automated reconnaissance framework for web applications with a focus on highly configurable streamlined recon process via Engines, recon data correlation and organization, continuous monitoring, backed by a database, and simple yet intuitive User Interface.

[reNgine](https://github.com/yogeshojha/rengine)



```
wget -P /tmp https://go.dev/dl/go1.24.4.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf /tmp/go1.24.4.linux-amd64.tar.gz
echo $SHELL
export PATH=$PATH:/usr/local/go/bin:/root/go/bin
go install -v github.com/projectdiscovery/nuclei/v3/cmd/nuclei@latest
go install github.com/hakluke/hakrawler@latest
CGO_ENABLED=1 go install github.com/projectdiscovery/katana/cmd/katana@latest
```

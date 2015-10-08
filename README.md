# This is Go Language Compiling Environment
## Version 1.5.1

#Use
```bash
docker pull index.tenxcloud.com/henjue/golang
```
```bash
docker run -t -i -v $(pwd):/go/src index.tenxcloud.com/henjue/golang
```
# or
```bash
docker run -d -p 2222:22 -e ROOT_PASS="mypass" index.tenxcloud.com/henjue/golang
```
```bash
docker run -d -p 2222:22 -e AUTHORIZED_KEYS="`cat ~/.ssh/id_rsa.pub`" index.tenxcloud.com/henjue/golang
```

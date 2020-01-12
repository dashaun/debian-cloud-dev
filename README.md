## Run this command to install everything in package.list

```
cat package.list | xargs -a <(awk '! /^ *(#|$)/' "$packagelist") -r -- sudo apt-get install -y
```

# Get the fly CLI from here https://github.com/concourse/concourse/releases/tag/v5.8.0
```
wget https://github.com/concourse/concourse/releases/download/v5.8.0/fly-5.8.0-linux-amd64.tgz
```

# Get YTT from here https://github.com/k14s/ytt/releases
```
wget https://github.com/k14s/ytt/releases/download/v0.24.0/ytt-linux-amd64
```

# Get yaml-patch from here  https://github.com/krishicks/yaml-patch/releases
```
wget https://github.com/krishicks/yaml-patch/releases/download/v0.0.10/yaml_patch_linux
```

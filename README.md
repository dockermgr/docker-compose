# Welcome to dockermgr TEMPLATE installer 👋
  
## Docker Compose template
  
### Requires scripts to be installed

```shell
 sudo bash -c "$(curl -LSs <https://github.com/dockermgr/installer/raw/main/install.sh>)"
 dockermgr --config && dockermgr install scripts  
```

#### Automatic install/update  

```shell
dockermgr install TEMPLATE
```


#### Manual install

```shell
git clone https://github.com/dockermgr/TEMPLATE "$HOME/.local/share/CasjaysDev/dockermgr/TEMPLATE"
bash -c "$HOME/.local/share/CasjaysDev/dockermgr/TEMPLATE/install.sh"
```
  
#### Just run it

```shell
mkdir -p "$HOME/.local/share/srv/docker/TEMPLATE/"

git clone <https://github.com/dockermgr/TEMPLATE> "$HOME/.local/share/CasjaysDev/dockermgr/TEMPLATE"

cp -Rfva "$HOME/.local/share/srv/docker/TEMPLATE/dataDir/." "$HOME/.local/share/srv/docker/TEMPLATE/"

cd "$HOME/.local/share/srv/docker/TEMPLATE/" && __sudo docker-compose -d

```

## Author  

👤 **Jason Hempstead**  

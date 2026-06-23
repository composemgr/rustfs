## 👋 Welcome to rustfs 🚀  

rustfs README

### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

### Install docker compose files

```shell
composemgr install rustfs
```

### Edit .env

```shell
$EDITOR "$HOME/.config/myscripts/composemgr/docker/$rustfs/.env"
```

### Edit app.env - will overwrite defaults from .env

```shell
$EDITOR "$HOME/.config/myscripts/composemgr/docker/$rustfs/app.env"
```

### Pull the containers

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$rustfs" pull
```

### Start the stack

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$rustfs" up &&
```

### Get the logs for the stack

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$rustfs" logs
```


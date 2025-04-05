# Actualizar el sistema
```sh
sudo dnf update -y
```
# Instalar los repositorios EPEL y Powerline
```sh
sudo dnf install -y epel-release
sudo dnf install -y https://repo.ius.io/ius-release-el9.rpm
```

# Instalar fish y cambiar el shell por defecto
```sh
sudo dnf install -y fish
sudo dnf install -y util-linux-user
chsh -s /usr/bin/fish
sudo dnf install -y powerline-fonts
```
# Instalar git
```sh
sudo dnf install -y git
```
# Reiniciar el sistema

```sh
restart
```
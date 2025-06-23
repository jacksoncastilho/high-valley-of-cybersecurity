### Criar link simbólico no /usr/local/bin
https://www.freecodecamp.org/portuguese/news/tutorial-de-symlink-no-linux-como-criar-e-remover-um-link-simbolico/
```
ln -s $PWD/example.sh /usr/local/bin/example
```
### Gerenciamento de pacote
```
# Atualizar repositorio de pacotes e atualizar os pacotes
apt update && apt upgrade -y

# Install package
apt install -y <package>

# Listar pacote instalado
apt list --instaled <package> # or dpkg -l | grep <package>

# Remover completamente pacote
apt remove --purge <package>

# Remover pacotes órfãs
apt autoremove
```

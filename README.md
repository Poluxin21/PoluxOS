# PoluxOS

Link for Download PoluxOS "Infrunami" Version: https://mega.nz/file/n7ACRCKC#6MT4xaLkBQ-3LZ_zs_TmallaKgLHF2GNKZLriH67Kdg ( GUI )


# Virtual Box

Para usar em Virtual Box:
Clique em "New"
Escolha o Tipo como "Linux" e Version em "Ubuntu 22.04"
Clique em Next
Base memory coloque em 4096
1 CPU ( Se preferir )
Clique em next
Na proxima vai aparecer para criar disco, deixa marcada a opção padrão e finalize a criação

Logo após clique na maquina e vá em "Settings"
Procure Storage e abaixo de "Controller IDE" Vai ter a opção de escolher um disco .iso
Clique no disco azul que aparece ao lado de opções de "Optical Drive" E escolha a iso
Inicie a maquina e siga o processo de instalaçao normalmente

+ Added Packages Initialize
  
```
- apt 
- htop
- iotop
- nload
- net-tools
- ip-utils
- openssh-server
- git

```

+ Added Secure Packages
  
```
- ufw ( Uncomplicated Firewall )
- fail2ban ( Brute force protect )

```

+ Added GNU UTILS

```
- coreutils ( ls, cp, mv, rm, etc )
- findutils ( find command to search file )
- grep
```



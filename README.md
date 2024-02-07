# AULA-LINUX- 7/2/24 -(1/4)

Exercício 1: Criar um container com o Debian e que seja interativo, que dentro dele tenha o neofetch.
  COMANDOS:
1- podman pull debian
2- podman run -it debian
3- apt update && apt install neofetch
4- [selecionar] "y"
5- neofetch

Exercício 2: Criar um container com o Debian destacável, que tenha python.
   COMANDOS:
1- podman run -dt debian
2-  podman exec -it NOME DO CONTAINER bash
3- apt update 
4- apt search python
5- apt install python3.11
6- [selecionar] "y" para continuar a instalação.

Exercício 3: Criar um container Fedora, interativo que tenha python e que tenha a ferramenta yt-dlp.
    COMANDOS:
  1- podman pull fedora
  2- podman run -it fedora
  3- dnf update && dnf install python.3
  4- (selecionar "y" para continuar)
  5- sudo dnf install yt-dlp
  6- (selecionar "y" para continuar).

  Exercício 4:
    COMANDOS:
  1-  podman pull fedora
  2- podman run -it fedora
  3- dnf update && dnf install python.3
  4- (selecionar "y" para continuar)
  5- sudo dnf install gallery-dl
  6- (selecionar "y" para continuar).

  

  

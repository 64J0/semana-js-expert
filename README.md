# Semana JS Expert - Netflix Bandersnatch

Este projeto está sendo desenvolvido com base nos vídeos do evento chamado Semana JS Expert, ministrado pelo Erick Wendel.

Nesse projeto nós iremos recriar o funcionamento da Netflix em que um filme pode ser interativo, ou seja, as próximas cenas são dependentes das escolhas do público.

Para tornar o carregamento do vídeo mais rápido será implementado um algoritmo que leva em consideração a conexão do usuário, sendo que em conexões com maior largura de banda são enviados vídeos com qualidade maior e em conexões piores são enviados vídeos com qualidade menor.

## Requisitos:

No decorrer das aulas são apresentados alguns programas que vamos utilizar. Abaixo segue uma listagem ensinando a baixar e instalar no Ubuntu 20.04.

* Node.js: https://nodejs.org/
* Repositório com o esqueleto da aplicação: https://github.com/ErickWendel/jsexpert01-skeleton-ew
* FFMPEG & FFProbe: https://ffmpeg.org/ffmpeg.html
* GPAC e MP4Box: https://github.com/gpac/gpac/wiki/GPAC-Build-Guide-for-Linux

* Informações sobre o suporte de navegadores a diferentes codecs de áudio e vídeo: https://gist.github.com/Vestride/278e13915894821e1d6f

## MP4Box:

```bash
# Navega até o diretório com os vídeos do bandersnatch
cd ./jsexpert01-skeleton-ew/assets/timeline

# Trás algumas informações importantes sobre o arquivo de vídeo
# Os mais importantes são:
# * A duração do vídeo
# * Os codecs de áudio e vídeo
MP4Box -info 01.intro-1920x1080.mp4
```

---
Vinícius Gajo Marques Oliveira, 2020

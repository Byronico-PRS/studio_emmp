# Configurações Ubuntu Studio

## Verificar a necessidade de drivers e instalar
```
sudo ubuntu-drivers autoinstall
```

## Instalar brave

```
sudo snap install brave
```

## Criar Atalhos 

### Apps
- Brave
- Konsole
- Libre Writer
- Krunner

### Kwin
- Fechar Janela
- Mostrar area de trabalho
- Mover janela para area de trabalho x
- Mudar para area de trabalho x

## Instalar Bismuth

```
sudo apt install kwin-bismuth
```

## Instalar repositorio dos kxstudio VER SITE

## Remover avldrums com pau

```
sudo apt remove avldrums.lv2 avldrums.lv2-soundfont
```

## Instalar Bismuth

```
sudo apt install kwin-bismuth
```

## Instalar suite kx e suite cadence

```
sudo apt install kxstudio-meta-audio-plugins-collection cadence gxplugins
```

## Instalar o Reaper
- Baixar o arquivo do site reaper.fm
- Rodar o arquivo de instalação.

## Instalar o sws e o reapack reeq
- Baixar os arquivos 
  - [Reapack](https://reapack.com/)
  - [SWS Extensions](https://www.sws-extension.org/)
  - [Reeq](https://forum.cockos.com/showthread.php?t=213501)
 

- Mover os arquivos para as pastas dentro da instalação do Reaper
  - Reapack na pasta UserPlugins
  - SWS Extensions na pasta do Reaper (Ele já vem separado em algumas pastas)
  - Reeq na pasta Effects
 
## Instalar a suite tukan
- No site do [Reaper Stash](https://stash.reaper.fm/)
- Procurar por Tukan plugins e copiar o endereço para o gerenciador de repositorios do reapack e então instalar os plugins

## Instalar Wine LinVST e rodar um plugin de windows no reaper
- Instalar o wine e o winetricks
```
sudo apt install wine winetricks
```
- Baixar o binário do [LinVST](https://github.com/osxmidi/LinVst/releases)
  - seguir as isntruçoes do linvst copiando os arquivos corretos para a pasta /usr/bin
  


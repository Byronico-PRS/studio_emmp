# Configurações Ubuntu Studio

## Verificar a necessidade de drivers e instalar
```
sudo ubuntu-drivers autoinstall
```

## Remover avldrums com pau
Esses pacotes causam conflito com pacoes do kxstudio, o que impedem a instalação do candence e de outros plugins que fazer o reaper funcionar bem, além de permitirem um uso do JACK que eu gosto masi do que o Qjack
```
sudo apt remove avldrums.lv2 avldrums.lv2-soundfont
```
## Instalar repositorio dos kxstudio
 - [Instruções](https://kx.studio/Repositories)

Para deixar o repositório funcional, não se esqueça de fazer um update do apt.
```
sudo apt update
```


## Instalar suite kx e suite cadence

```
sudo apt install kxstudio-meta-audio-plugins-collection cadence gxplugins
```

## Instalar Nix
Esse é um ótimo repositório de programas, que dificilmente quebram, atualizam facilmente, instalaremos o reaper e o brave por este repositṍrio.

 - [Siga as instruções](https://nixos.org/)

## Instalar programas do repositório nix

Como existem aplicativos unfree vc deve ter que colocar um comando para permitir a instalação desses pacotes.
Para permitir temporariamente a instalação desses pacotes execute o seguinte comando:

```
export NIXPKGS_ALLOW_UNFREE=1
```
E para instalar os pacotes:

[Brave](https://brave.com/pt-br/) - Browser para navegação na Internet

[Reaper](https://www.reaper.fm/) - DAW para trabalho com áudio

[Timeshift](https://github.com/teejee2008/timeshift) - Para criar pontos de restauração do seu sistema

[Vscode](https://code.visualstudio.com/) - Editor de texto

[Neofetch](https://github.com/dylanaraps/neofetch) - App que traz informações do seu sistema pelo terminal


```
nix-env -iA nixpkgs.brave nixpkgs.reaper nixpkgs.timeshift nixpkgs.vscode nixpkgs.neofetch
```

## Criar Atalhos 

Lembre-se de colocar esses pacotes minstalados pelo nix no lançador de aplicativos, todos os executáveis se encontram no diretório no diretório:

~/.nix-profile/bin/

### Apps
os arquvos executáveis de cada pacote são:
- Brave - brave
- Reaper - reaper
- Timeshift - timeshift-launcher
- Vscode - code


## Instalar o sws e o reapack reeq

É possível instalar algums extensões no reaper para que ele tenha mais funcionalidades:

### Baixar os arquivos 
  - [Reapack](https://reapack.com/)
  - [SWS Extensions](https://www.sws-extension.org/)
  - [Reeq](https://forum.cockos.com/showthread.php?t=213501)
 
### Mover os arquivos para as pastas dentro da instalação do Reaper
 Lembre-se de procurar a pasta de instalação do reaper dentro do próprio reaper na opção:
 
 >Options>Show REAPER resource path in explorer
  
  - Reapack na pasta UserPlugins
  - SWS Extensions na pasta do Reaper (Ele já vem separado em algumas pastas)
  - Reeq na pasta Effects

 
## Instalar a suite tukan
 Suite de plugins para o reaper:
 
- No site do [Reaper Stash](https://stash.reaper.fm/)
- Procurar por Tukan plugins e copiar o endereço para o gerenciador de repositorios do reapack e então instalar os plugins

 
Se você pretende rodar algum app para windows ou plugins para windows não se esqueça:

## Instalar Wine LinVST e rodar um plugin de windows no reaper
- Instalar o wine e o winetricks
```
sudo apt install wine winetricks
```
- Baixar o binário do [LinVST](https://github.com/osxmidi/LinVst/releases)
  - seguir as [instruções](https://github.com/osxmidi/LinVst/wiki) do linvst copiando os arquivos corretos para a pasta /usr/bin
  
## Configurar seu workflow no Plasma
Cada pessoa tem a sua maneira de trabalhar, aquie só escrevi minhas configurações para não me esquecer 


## Instalar Bismuth

```
sudo apt install kwin-bismuth
```
### Kwin
- Fechar Janela
- Mostrar area de trabalho
- Mover janela para area de trabalho x
- Mudar para area de trabalho x



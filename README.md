# AACOMPI

Este repositório se destina a Atividade Acadêmica de Computação I da UFRRJ. O trabalho consiste em um Jogo no estilo Tower Defense desenvolvido em C e SDL2.

#### Colaboradores do projeto

+ [Andressa Oliveira](https://github.com/a-oliveira) (Desenvolvedor2)

+ [Thiago Frazão](https://github.com/ThiagoFrazao) (Game Design)


![img1](https://user-images.githubusercontent.com/9852787/57247781-20e5ca80-7017-11e9-8a3b-287b059d5a16.png)
![img2](https://user-images.githubusercontent.com/9852787/57247783-20e5ca80-7017-11e9-8be0-e58e8146c491.png)

#### Para executar o jogo deve-se instalar a biblioteca SDL2 e alguns pacotes auxiliares.

##### Instalar SDL2 no Linux

- sudo apt-get install libsdl2-dev && sudo apt-get install libsdl2-dbg && sudo apt-get install libsdl2-dev 

##### Instalar pacotes adicionais SDL2

ttf
- sudo apt-get install libsdl2-ttf-2.0-0 && sudo apt-get install libsdl2-ttf-dev && sudo apt-get install libsdl2-ttf-dbg

mixer
- sudo apt-get install libsdl2-mixer-2.0-0 && sudo apt-get install libsdl2-mixer-dbg && sudo apt-get install libsdl2-mixer-dev

gfx
- sudo apt-get install libsdl2-gfx-1.0-0 && sudo apt-get install libsdl2-gfx-dev && sudo apt-get install libsdl2-gfx-dbg

image
- sudo apt-get install libsdl2-image-2.0-0 && sudo apt-get install libsdl2-image-dbg && sudo apt-get install libsdl2-image-dev 

##### Compilação e execução

- Compilação

Para compilar o jogo use: gcc jogo.c -o jogo -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer -lSDL2_gfx -lm

- Execução

Para executar o jogo use: ./jogo

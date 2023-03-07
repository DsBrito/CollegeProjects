# Embarcados Jogo Ping-Pong
Projeto de Laboratório (PL) - Jogo de Ping Pong
 
Trata-se de implementar um jogo. 

![image](https://user-images.githubusercontent.com/80075307/201693806-7a5f9a1e-d6a9-48f2-9486-254ae2aacd1f.png)

O segmento de reta de 50 pixels representa uma raquete que se move somente na direção vertical, 
em ambos os sentidos, usando-se as teclas “u” e “d” para deslocar a raquete para cima e para baixo, respectivamente. 

A velocidade da bolinha deve ser controlada pelas teclas “+” e “-“, do teclado numérico. 

A bola vermelha se move e todas as vezes em que o jogador consegue rebater a bola, deve-se adicionar 1 ponto ao placar do jogador. 

Caso o jogador não consiga rebater a bola e a mesma se choca com a lateral direita da tela, deve-se adicionar 1 ponto ao placar do computador. 

Um placar de dois dígitos  contabiliza a pontuação. 
Para sair do jogo, deve-se pressionar a tecla “Esc”. 

A localização horizontal da raquete está determinada na figura.


<h3 align="left">Iniciação</h3>
   </a>
   <p align="justify">

É necessário ter o software dosbox instalado e montar uma pasta de drivers.(Tutorial de como montar a pasta 
     <a href="http://www.sierrahelp.com/Utilities/Emulators/DOSBox/DOSBoxGuide-Mount.html"
        >aqui). 
      ![image](https://user-images.githubusercontent.com/80075307/223241048-89caea4f-cba3-4ff9-b220-255a0714f273.png)
    
 
<h3 align="left"> Pré - Execução  </h3>
   </a>
   <p align="justify">
 É necessário ter os arquivos da pasta frasm no mesmo nível do arquivo do código do jogo (dsb.nasm).


![image](https://user-images.githubusercontent.com/80075307/223243621-d46676e8-35ed-449c-bd4f-390d549e2a75.png)



  <h3 align="left">Execução</h3>
    </a>
    <p align="justify">
    Para executar deve antes inserir os seguintes comandos: 
    
    
    nasm dsb
    freelink dsb
    dsb.exe

![image](https://user-images.githubusercontent.com/80075307/223264756-d9876806-f622-4e4b-80b6-d2f04b3485fb.png)

<h3 align="left"> Em Execução  </h3>
   </a>
   <p align="justify">
   
![image](https://user-images.githubusercontent.com/80075307/223231198-75f04131-3507-4c30-9356-294a6fbc8998.png)


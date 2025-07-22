# Projeto_Sensores_Altitude_Temperatura 
Repositório criado para versionamento da sobre sensores de temperatura e pressão da residência em software embarcado, com implementação de um sistema de monitoramento 


## Descrição geral do Funcionamento do programa 
Os LEDs RGB mostram a cor de acordo com a temperatura medida pelo sensor BMP280, sendo branco para temperatura menor ou igual a 20 °C, azul  para temperaturas entre 20 e 30 °C, e vermelho para temperaturas maiores ou igual a 30°C. No Display da BitDogLab são informadas simultaneamente as leituras de temperatura e altitude para o sensor BMP280 e de temperatura e pressão para o sensor AHT10. Um sinal sonoro é emitido pelo buzzer indicando o monitoramento constante dos parâmetros.  

## Descrição detalhada do Funcionamento do programa  na BitDogLab
**Botão B→** Utilizado para colocar a placa em modo bootssel.

**LEDs RGB→** Cor de acordo a temperatura do BMP280.

**Display→** Utilizado para mostrar os parâmetros medidos.

**Buzzer→** Utilizado para emitir sinal sonoro de funcionamento. 


## Compilação e Execução

1. Certifique-se de que o SDK do Raspberry Pi Pico está configurado no seu ambiente.
2. Compile o programa utilizando a extensão **Raspberry Pi Pico Project** no VS Code:
   - Abra o projeto no VS Code, na pasta **Projeto_Sensores_Altitude_Temperatura** tem os arquivos necessários para importar 
   o projeto com a extensão **Raspberry Pi Pico Project**.
   - Vá até a extensão do **Raspberry pi pico project** e após importar (escolher sdk de sua escolha) os projetos  clique em **Compile Project**.
3. Coloque a placa em modo BOOTSEL e copie o arquivo `bmp_aht_disp.uf2`  que está na pasta build, para a BitDogLab conectado via USB.

**OBS: Devem importar o projeto para gerar a pasta build, pois a mesma não foi inserida no repositório**

## Colaboradores
- [PauloCesar53 - Paulo César de Jesus Di Lauro ] (https://github.com/PauloCesar53)

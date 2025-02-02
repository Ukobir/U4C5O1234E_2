# Atividade parte 2 da aula síncrona do dia 29/01 do curso de sistemas embarcados oferecido pela Embarcatech
## Descrição
Este código tem a finalidade de ligar os 3 leds ao acionar o Notão A, de modo que a cada 3 segundos um led é apagado até que em 9 segundos todos apaguem. Podendo ser ligados novamente, somente, passsado estes 9 segundos. 
A implementação utiliza interrupçao por temporização e por mudança de estado da gpio (ao acionar o Botão A). Conta também com a implementação da redução do efeito debouncing via software.


Obs: Na simulação apresenta 3 leds: azul, verde e vermelho. Já na placa Bitdoglab liga apenas um LED RGB que alterna as cores na seguinte ordem: Branco (verde + azul + vermelho), roxo (azul + vermelho) e apenas vermelho até se apagar.

## Pré-requesitos
- VS Code 
- Pico sdk
- Wokwi para o Vscode
- Placa Bitdoglab 

## Instalação
1. Clone o repositório:
   ```sh
   git clone https://github.com/Ukobir/U4C5O1234E_2.git
2. Compile no Pico-SDK
3. Faça o Upload para a placa Bitdoglab ou Simule utilizando o Wokwi.

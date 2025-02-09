# Jadson de Jesus Santos - Tarefa de Comunicação Serial

## 📚 Apresentação

Para consolidar os conceitos sobre o uso de interfaces de comunicação serial no RP2040 e explorar as funcionalidades da placa de desenvolvimento BitDogLab, 
propõe-se a realização da seguinte tarefa individual prática

## 🎯 Objetivo

- Compreender o funcionamento e a aplicação de comunicação serial em microcontroladores.
- Aplicar os conhecimentos adquiridos sobre UART e I2C na prática.
- Manipular e controlar LEDs comuns e LEDs endereçáveis WS2812.
- Fixar o estudo do uso botões de acionamento, interrupções e Debounce.
- Desenvolver um projeto funcional que combine hardware e software.

## 📑 Requisitos

- Visual Studio Code;
- Extensões C/C++, CMAKE e Raspberry Pi Pico no VSCode;
- Comunicação I2C e UART.
- Plataforma de Desenvolvimento BitDogLab com placa Raspberry Pi Pico W.

## 📋 Funcionamento

- O Display Oled exibe caracteres que serão digitados no Monitor Serial;
- Os Botões possuem debounce por meio software;
- O Botão A alterna o estado do LED Verde e também exibe no Display Oled;
- O Botão B alterna o estado do LED Azul e também exibe no Display Oled;
- Quando um valor numérico de 0 a 9 é digitado, a matriz de LED exibe o valor;
- Utiliza-se UART para comunicação serial e I2C para comunicação com o Display.

## 📷 GIF Ilustrativo

![Gif](https://github.com/user-attachments/assets/9b7cd4cb-ac57-42dc-8063-5b88a66c1ebb)

## ▶️ Link do Vídeo: https://youtu.be/hQUEw9TN1Kg

# Mixclub Music - Aula COGU

Bem-vindo ao repositório do projeto **Mixclub Music - Aula COGU**! Este projeto foi desenvolvido como parte de uma aula para o **Mixclub**, um grupo formado por integrantes da **@radiocafuné** — uma rádio online da qual faço parte.

Sobre o Projeto

Este repositório contém exemplos de código e anotações utilizados em uma aula de **Live Coding**, com foco na criação de música usando sintetizadores, baterias eletrônicas e efeitos sonoros. O objetivo é aprender e compartilhar conhecimentos sobre programação musical em tempo real.

Apresentação Final

A aula termina com uma música criada durante a sessão, demonstrando o que é possível fazer com as ferramentas e técnicas apresentadas.

Ferramentas Utilizadas

- Linguagem de programação musical (ex: TidalCycles dentro da plataforma STRUDEL)
- Sintetizadores e samples
- Efeitos sonoros (cutoff, delay, gain, etc.)
- Drum machines virtuais (Roland TR-808, TR-707, Akai XR10, etc.)

Estrutura do Arquivo

O arquivo `Mixclub Music -Aula COGU - 25-11-2025.txt` contém:

- Comandos para tocar e pausar sons
- Exemplos de criação de notas musicais e baterias
- Personalização de sons e parâmetros
- Uso de waveforms e efeitos
- Padrões de sons preferidos (ex: guitarra muted, koto, slap bass)
- Exemplos de basslines e grooves

Trechos de Exemplo

```javascript
// Exemplo de bateria
s("bd*4, [- cp]*2 - - , [- hh]*4").gain(8).bank("RolandTR707")

// Exemplo de bassline
n("c g*2 @2 e - c").sound("xylophone_soft_ff").gain(3)
```

Como Usar

1. Instale o ambiente de Live Coding de sua preferência
2. Copie e cole os trechos de código no seu ambiente
3. Modifique os parâmetros para criar seus próprios sons
4. Experimente combinar diferentes padrões e efeitos

Objetivo

Estou estudando **Live Coding** para me apresentar na cidade, com o objetivo de aprender bem a técnica para poder tocar em eventos e compartilhar experiências musicais através da programação.

Contato

- @felipecogumello no inta
  
*Obrigado por escutarem até aqui! É o fim!* 🎶

Espero que este material possa ajudar outras pessoas que estão começando no mundo do Live Coding e da programação musical!

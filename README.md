# Circuistos Digitais - Trabalho

Entrega do trabalho de Circuitos Digitais realizado pela dupla Thiago Nerton e Luana Teles.

Este README fornece informações sobre a atribuição, como configurar e executar o projeto, e detalhes adicionais.

## Sumário
- [Descrição](#descrição)
- [Seções do Circuito](#seções-do-circuito)
  - [Main](#main)
  - [Timer](#timer)
  - [Core](#core)
- [Utilização](#utilização)
- [Instalação](#instalação)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Descrição

**Sobre o Jogo:**
O "Guess the Number" com uma limitação de 15 pontos e um tempo máximo de 60 minutos é uma versão compacta e desafiadora do clássico jogo de adivinhação de números.

**Objetivo:**
Acertar o número secreto dentro de um intervalo específico, tudo isso em uma experiência que pode ser concluída em até 60 minutos. O "Guess the Number" nesta versão é cativante pela sua natureza rápida e desafiadora, oferecendo uma experiência intensa e gratificante para testar as habilidades de dedução numérica dos jogadores.

**Funcionamento do Jogo:**
Os jogadores determinam o tempo do jogo no cronômetro e pressionam os botões COMEÇAR e SELECT, respectivamente. Cada jogador dá um palpite para as coordenadas X e Y, confirma seus chutes e troca de jogador. Ganha quem fizer 15 pontos primeiro ou tiver mais pontos quando o tempo acabar.

## Seções do Circuito

### Main
![Panorama](caminho/para/a/imagem.jpg)
Aqui está o jogo junto com as caixas dos sistemas CORE e TIMER.

### Timer
O TIMER (cronômetro) utiliza 16 Flip-Flops tipo D para representar unidades, dezenas de segundos e minutos. Multiplexadores auxiliam no pulso do clock nos Flip-Flops.

[Tabela Verdade do Contador de Dezenas](fotos/cont_d)
[Tabela Verdade do Contador de Unidades](fotos/cont_u)

### Core
O CORE é onde o jogo acontece, com INPUT_LOGIC para receber chutes, GERADOR DE NÚMEROS, COMPARADOR e CONTADOR para pontuação. Inclui também um sistema de mudança de relógio ao trocar de jogador.

[Circuito Input_Logic](fotos/core_input-logic)
[Circuito Placar](fotos/core_placar)

## Utilização

Instruções de utilização aqui...

## Instalação

```bash
# Comando de Instalação
git clone https://github.com/nerton1/Advinhe_o_Numero-Acentuado.git
cd Advinhe_o_Numero-Acentuado

# Comando Adicional
melhore

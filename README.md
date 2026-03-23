[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tro2Z-6l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23170935&assignment_repo_type=AssignmentRepo)
# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:** Sarah de Oliveira Soares 
**Matrícula:** 20251100147
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 10). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 10.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 10, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*

## 2. Evidência Visual (Screenshot)
*Suba o screenshot da sua solução final (onde aparece "Você resolveu este nível!") para a pasta **/imagens** deste repositório.*

## 3. Estratégia Utilizada
*Explique com suas palavras como você resolveu o problema. Qual foi a lógica?*
> Primeiro, eu usei o looping X5 com movimentação angular para direita à 144°, no tamanho 50 para ter uma forma de estrela; depois adicionei esse looping dentro de outro X3 com especificações de movimentação para que a cada estrela desenhada, a proxima fosse desenhada em outra rotação. "Tirei o lápis da tela" para ele não "rabiscar"
onde eu não queria e segui para a esquerda; "coloquei o lapis de volta" e vim com outro looping, dessa vez X360, que tinha especificações para desenhar muitos traços vindo do centro do círculo(1°) para a extremidade(90°) de acordo com o tamanho(50) dele. Esse processo foi repetido no segundo círculo, feito para simular a fase da lua, que apenas foi posicionado mais a direita e acima.



## 4. Desafio:
**A)** O looping X6 com ângulo a 60° graus.
  
**B)** Usando o ângulo reto(90°).
  
**C)** Paraa questão A, levando em consideração que o hexágono, que tem 6 lados, ia fazer a figura do círculo, e o círculo tem 360° graus, so fiz a divisão.
Ex:. 360|6_
      00|60
---    0
       
Para questão B, eu usei o raciocínio de que dentro de um circulo existe as vértices dele que formam um quadrado, e posicionados nessas vértices, os 4 hexágonos ficariam igualmente distribuidos, eu calculei outra divisão.
Ex:.  360|4_
       00|90
---     0

@Annabell

# mario-project

# 🏁 Jogo de Corrida do Mario (Node.js)

Um projeto divertido feito em **Node.js**, simulando uma corrida entre personagens clássicos da franquia Mario: **Mario, Luigi, Peach, Toad e Yoshi**. O jogo é executado no terminal e se desenvolve ao longo de **5 rodadas**, com diferentes tipos de desafio em cada uma.

---

## 🎮 Como Funciona

O jogo simula 5 rodadas entre os personagens, com 3 tipos de modo:

### 🚀 Modos de Rodada

- **Reta**:  
  Cada personagem rola um dado de 6 lados (D6) e soma com o seu atributo de velocidade.  
  Quem tiver a maior soma, ganha **1 ponto**.

- **Curva**:  
  Semelhante à reta, mas soma-se o dado com o atributo de manobrabilidade.  
  Quem tiver a maior soma, ganha **1 ponto**.

- **Confronto**:  
  Aqui o foco é o **atributo de poder**.  
  Cada personagem rola um D6 e soma ao seu poder.  
  Quem tiver a **menor soma perde 1 ponto** (se tiver mais de 0 pontos).  
  - Caso a pontuação já seja 0, não perde nada.

---

## 👾 Personagens

- **Mario**
- **Luigi**
- **Peach**
- **Toad**
- **Yoshi**

Cada personagem possui atributos pré-definidos como:

- Velocidade
- Manobrabilidade
- Poder
- Pontos (inicialmente 0)

---

## 🧠 Regras

- O jogo roda automaticamente.
- Cada rodada escolhe aleatoriamente entre os três modos.
- Ao final das 5 rodadas, o personagem com **mais pontos** vence a corrida.
- Empates são possíveis.

## ✍️ Autor

Brenda Oliveira  
[LinkedIn](https://www.linkedin.com/in/brenda-oliveira-455415235/)


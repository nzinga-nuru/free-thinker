---
layout: course
title: "Capítulo 1"
course: curso1
module: modulo1
---

#capacitância #dielétrico #capacitor #associação-em-série #associação-em-paralelo #rigidez-dielétrica #constante-dielétrica 

## O que é um capacitor?
---

Um **capacitor** é uma **configuração de dois condutores eletricamente isolados**, chamados de **placas**, dispostos de forma que haja um **meio isolante** entre eles — que pode ser o **vácuo**, o **ar** ou um **material dielétrico**.

Quando uma **diferença de potencial** é aplicada entre esses condutores, surgem cargas de **módulo igual e sinais opostos** em cada placa: uma acumula carga $+Q$ e a outra $−Q$. Esse **acúmulo não resulta de uma corrente contínua entre as placas, mas sim da separação de cargas induzida pela diferença de potencial.**

**A capacitância $C$ depende unicamente da geometria do sistema e da natureza do meio entre os condutores.**


**NOTAS:**

> - O campo elétrico entre as placas **não é necessariamente uniforme** em qualquer capacitor. Ele é aproximadamente uniforme apenas no capacitor plano ideal, com placas extensas e paralelas, e separadas por uma distância pequena em relação ao seu tamanho. Em configurações como **esferas concêntricas ou cilindros coaxiais** (como resolvemos em sala), o campo varia com a posição.
>
> - Cada condutor individual é chamado de “placa”, mesmo que tenha geometria não plana. O termo “placa” generaliza aqui a ideia de “superfície condutora onde ocorre acúmulo de carga”.
  

## Definição Formal de Capacitância
---

A grandeza física que caracteriza um capacitor é a capacitância, definida como:

$$C = \dfrac{Q}{\Delta V}$$

onde:
- $C$ é a capacitância (em farad, F),
- $Q$ é a carga armazenada em uma das placas,
- $\Delta V$ é a diferença de potencial entre as placas.

A capacitância mede a capacidade do capacitor de armazenar carga elétrica por unidade de diferença de potencial. Quanto maior a capacitância, mais carga ele consegue armazenar para uma mesma voltagem.

## Analogia Intuitiva: Balde de Água
---
Podemos pensar em um capacitor como um balde que armazena água:
- A carga elétrica é como a quantidade de água armazenada.
- A diferença de potencial é como a altura da água (a pressão).
- A capacitância é como o tamanho do balde — quanto maior, mais água (carga) ele pode armazenar para uma mesma altura (diferença de potencial).

## Aplicações dos Capacitores
---
Capacitores estão presentes em praticamente todos os dispositivos eletrônicos. Algumas aplicações:

- Fontes de alimentação: armazenam energia para suavizar oscilações de tensão.
- Câmeras fotográficas: carregam rapidamente e liberam uma descarga para o flash.
- Filtros eletrônicos: em conjunto com resistores e indutores, moldam sinais elétricos.
- Circuitos temporizadores (RC): controlam intervalos de tempo em circuitos digitais.


## O que é um dielétrico?
---
Um dielétrico é um material isolante (como vidro, mica, cerâmica ou plástico) que pode ser inserido entre as placas de um capacitor. Ao contrário dos condutores, ele não permite o fluxo de cargas livres, mas pode ser polarizado quando submetido a um campo elétrico.

### Como o dielétrico afeta a capacitância?

Ao inserir um dielétrico entre as placas de um capacitor, sua capacitância aumenta. A nova capacitância $C^{\prime}$ é dada por:

$$C^{\prime} = \kappa \cdot C_0$$
onde:
- $C_0$ é a capacitância no vácuo ou ar,
- $\kappa$ é a constante dielétrica do material (sempre $\kappa > 1$).

Isso significa que, para a mesma diferença de potencial, o capacitor pode armazenar mais carga.

### O que acontece com a energia armazenada?

Depende de como o dielétrico é inserido. Vamos analisar dois casos:

**(a) Capacitor conectado à fonte de tensão (tensão constante)**

Se o capacitor permanece ligado à fonte de tensão enquanto o dielétrico é inserido:

- A carga acumulada aumenta,
- A capacitância aumenta,
- E a energia armazenada também aumenta:

$$U = \frac{1}{2} C \Delta V^2$$
Como $\Delta V$ é constante e $C$ aumenta, então $U$ aumenta.

  
#### Exemplo:

Um capacitor plano de $10 \, \mu\text{F}$ está conectado a uma bateria de $12 V$.
Energia inicial:

$$U = \frac{1}{2} \cdot 10 \times 10^{-6} \cdot 12^2 = 0{,}00072 \, \text{J} = 0{,}72 \, \text{mJ}$$

  

Agora inserimos um dielétrico com $\kappa = 3$:

Nova capacitância $C^{\prime} = 30 \, \mu\text{F}$

$$U^{\prime} = \frac{1}{2} \cdot 30 \times 10^{-6} \cdot 12^2 = 0{,}00216 \, \text{J} = 2{,}16 \, \text{mJ}$$

A energia triplica, acompanhando o aumento da capacitância.

**(b) Capacitor isolado (carga constante)**

Se o capacitor foi carregado e desconectado da fonte antes da inserção do dielétrico:
- A carga Q permanece constante,
- A capacitância aumenta,
- A diferença de potencial diminui,
- A energia armazenada diminui:

$$U = \frac{Q^2}{2C}$$

Parte da energia é dissipada no processo de polarização do dielétrico.


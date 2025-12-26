# Otto Wheels Modificado com Caçamba para Transporte Eficiente

##  Descrição do Projeto

Este projeto tem como objetivo o desenvolvimento e a modificação do robô **Otto Wheels**, por meio da adição de uma **caçamba**, visando o **transporte eficiente de cargas leves**. A modificação amplia as funcionalidades originais do robô, tornando-o mais versátil e aplicável a cenários de transporte automatizado, com foco em eficiência, mobilidade e organização.

Para o planejamento e melhor compreensão do comportamento funcional do robô, foi utilizada a **Rede de Petri**, permitindo a modelagem dos estados, transições e fluxos operacionais do sistema. Essa abordagem auxilia na projeção das funções do robô, facilitando a identificação de sequências lógicas e prevenindo conflitos durante a execução das tarefas.

A **modelagem tridimensional (3D)** do robô e de suas modificações estruturais foi desenvolvida no software **Fusion 360**, possibilitando a visualização detalhada dos componentes, a análise dimensional e a correta integração da caçamba à estrutura do Otto Wheels.

Além disso, o projeto foi documentado e apresentado utilizando a plataforma **Overleaf**, com o objetivo de aprimorar o aprendizado em **codificação LaTeX** e organizar a apresentação do projeto por meio de **slides e documentos acadêmicos** de forma padronizada.

---

##  Metodologia Utilizada

- Modelagem funcional com **Rede de Petri**
- Modelagem estrutural 3D no **Fusion 360**
- Documentação e apresentação em **LaTeX (Overleaf)**
- Impressão 3D das peças modificadas

---

##  Modelagem 3D e Impressão

Para a reprodução deste projeto, recomenda-se a utilização dos **arquivos STL desenvolvidos pela equipe**, os quais já estão prontos para impressão 3D.

###  Passo a passo recomendado:

1. Abra o **Fusion 360**.
2. Importe os arquivos **STL fornecidos neste repositório**.
3. Analise as dimensões e o encaixe das peças em relação à estrutura original do Otto Wheels.
4. Caso desejado, realize **modificações personalizadas**, como ajustes dimensionais ou alterações no formato da caçamba.
5. Exporte os arquivos finais em formato **STL**.
6. Realize a **impressão 3D** (recomenda-se PLA).
7. Monte as peças no robô e verifique o funcionamento do conjunto.

## Passo a passo montagem do robô
🧱 1. Identificação das partes do robô (modelo da imagem)

Pelo modelo 3D, o robô é composto por:

Módulo frontal (amarelo) → cabeça do Otto (sensor ultrassônico)

Base frontal (azul) → suporte da cabeça e das rodas grandes

Base traseira (azul) → compartimento eletrônico e bateria

6 rodas

2 rodas grandes laterais (tração)

4 rodas menores traseiras (apoio/estabilidade)

Motores DC (acoplados às rodas grandes)

Arduino Nano

Driver de motores

Sensor ultrassônico

Servo motor (movimento da cabeça)

Suporte de bateria

🔩 2. Montagem da base traseira (chassi principal)

Pegue a base traseira azul (parte maior).

Fixe:

O suporte de bateria no fundo da base

O driver de motores em uma área central

O Arduino Nano em local elevado ou lateral

Garanta que:

As portas do Arduino fiquem acessíveis

Os fios possam passar para a parte frontal

👉 Essa base funciona como o “cérebro” do robô.

⚙️ 3. Instalação dos motores e rodas grandes

Encaixe os motores DC nas laterais da base frontal azul.

Fixe os motores com parafusos ou encaixe do próprio chassi.

Acople as rodas grandes diretamente no eixo dos motores.

Verifique se:

As rodas giram livremente

Estão bem alinhadas para evitar desvio

Essas rodas são responsáveis pelo movimento principal do robô.

🛞 4. Montagem das rodas traseiras menores

Na base traseira, fixe as rodas menores:

Uma de cada lado

Essas rodas:

Não são motorizadas

Servem para equilíbrio e estabilidade

Confirme que todas as rodas tocam o solo igualmente.

🧠 5. Fixação da cabeça (parte amarela)

Encaixe a cabeça amarela sobre a base frontal.

Antes de fechar completamente:

Instale o sensor ultrassônico nos dois furos frontais (“olhos”)

Passe os fios do sensor para dentro do corpo.

Parafuse ou encaixe a cabeça firmemente.

🔄 6. Instalação do servo motor

Fixe o servo motor entre a base frontal e a cabeça.

O eixo do servo deve:

Permitir movimento lateral da cabeça

Centralize o servo antes de fixar a cabeça definitivamente.

🔌 7. Ligações elétricas
Motores

Motores → Driver de motores

Driver → Arduino (pinos digitais)

Sensor ultrassônico

VCC → 5V do Arduino

GND → GND

TRIG → pino digital

ECHO → pino digital

Servo motor

Vermelho → 5V

Marrom/Preto → GND

Amarelo → pino PWM

Alimentação

Bateria → Driver de motores

Driver → Arduino (VIN ou 5V, conforme o projeto)

⚠️ Atenção à polaridade para evitar danos.

💻 8. Programação

Conecte o Arduino ao computador.

Abra a IDE do Arduino.

Instale bibliotecas necessárias (ex.: OttoDIY, Servo).

Carregue o código do Otto Wheels.

Faça o upload.

✅ 9. Testes finais

Ligue o robô.

Verifique:

Se as rodas giram corretamente

Se a cabeça se movimenta

Se o sensor detecta obstáculos

Ajuste:

Sentido dos motores

Ângulo do servo

Sensibilidade do sensor
---

## 📂 Estrutura do Repositório

```text
├── README.md
├── modelagem_3d/
│   ├── cacamba.stl
│   ├── suporte.stl
│   └── montagem.f3d
├── redes_de_petri/
│   └── modelo_rede_petri.pdf
├── overleaf/
│   ├── slides.pdf
│   └── artigo.tex
└── imagens/
    └── otto_wheels_modificado.png




## 😂 Autores

- Gabriel Santana  
- Marcelo Machado  
- Evandro Henrique


Projeto desenvolvido para fins acadêmicos, com possibilidade de reprodução e aprimoramento em trabalhos futuros.

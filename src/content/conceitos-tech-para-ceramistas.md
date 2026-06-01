# 🏺 Conceitos de Tecnologia para Ceramistas (e Outros Artistas)

> *"Se percebes de cerâmica, já percebes de tecnologia. Só não sabias."*

---

## 1. Stack (Pilha Tecnológica)

**O que é:** Um conjunto de camadas de software que trabalham juntas, como as camadas de um vidrado.

**Na cerâmica:** Uma peça tem a argila (base), o engobe (camada intermédia) e o vidrado (camada final). Cada camada depende da anterior.

**Na tecnologia:** O ANARI tem:
- **Argila (Base):** Ubuntu Linux — o sistema operativo que faz tudo funcionar
- **Engobe (Intermédio):** Python + FastAPI — a linguagem que dá forma à lógica
- **Vidrado (Final):** React + Vite — a interface que o utilizador vê e toca

**Exemplo prático:** Quando o Manuel aplica um vidrado, ele sabe que a argila tem de estar bem cozida primeiro. Na tecnologia é igual: a interface (vidrado) só funciona se o servidor (argila) estiver a correr.

---

## 2. Pipeline (Fluxo de Trabalho)

**O que é:** Uma sequência de passos que transformam algo bruto em algo acabado.

**Na cerâmica:** O processo de criar uma peça:
1. Extrair a argila → 2. Amassar → 3. Modelar → 4. Secar → 5. Cozer (chacota) → 6. Vidrar → 7. Cozer novamente

**Na tecnologia:** O ANARI processa um comando assim:
1. **Intent Engine:** "O que é que o Manuel quer fazer?"
2. **Planner:** "Como é que eu faço isso?"
3. **Executor:** "Que ferramenta(s) vou usar?"
4. **Memory:** "O que já aprendi com isto?"

**Exemplo prático:** Quando fazes uma peça na roda, não começas pelo vidrado. Segues uma ordem. O ANARI também.

---

## 3. API (Interface de Programação de Aplicações)

**O que é:** Uma ponte que permite que duas coisas conversem entre si.

**Na cerâmica:** O torno é uma API entre as tuas mãos e a argila. As tuas mãos não tocam diretamente na argila em rotação; o torno faz a mediação.

**Na tecnologia:** A API do IPMA permite que o ANARI pergunte "como está o tempo em Penafiel?" e receba uma resposta com dados.

**Exemplo prático:** Quando queres saber a temperatura do forno, não metes a mão lá dentro. Usas um pirómetro (a "API" do forno).

---

## 4. Open Source (Código Aberto)

**O que é:** Software cujo "código-fonte" está disponível para qualquer pessoa ver, modificar e partilhar.

**Na cerâmica:** É como uma receita de vidrado que um ceramista partilha abertamente, em vez de a manter em segredo.

**Exemplo prático:** O ANARI é open source. Qualquer pessoa pode ver como foi construído, adaptá-lo às suas necessidades, e partilhar as suas melhorias com a comunidade.

---

## 5. Memória e Contexto

**O que é:** A capacidade de um sistema se "lembrar" do que aconteceu antes para tomar melhores decisões agora.

**Na cerâmica:** Sabes que uma determinada argila racha se secar muito rápido. Essa é a tua "memória de ceramista". Da próxima vez que usares essa argila, tomas precauções.

**Na tecnologia:** O ANARI tem um módulo chamado **AnariSelf** que observa cada interação, deteta padrões, e aprende com eles.

**Exemplo prático:** Se perguntares muitas vezes sobre esmaltes de cone 10, o ANARI aprende que esse é um tema importante para ti e passa a sugeri-lo ou a preparar informação sobre isso.

---

## 6. Modelo de IA (Large Language Model)

**O que é:** Um programa que aprendeu a "conversar" lendo uma quantidade enorme de texto.

**Na cerâmica:** É como um aprendiz que passou 10 anos a ler todos os livros de cerâmica do mundo. Sabe muito sobre cerâmica, mas nunca tocou em argila.

**Na tecnologia:** O ANARI usa 3 modelos locais:
- **Llama 3.1** (4.7GB): conversa rápida, tarefas simples
- **Qwen 3** (9.3GB): raciocínio profundo, análise
- **Gemma 3** (8.1GB): criatividade, escrita

**Exemplo prático:** O Llama 3.1 é como um assistente de atelier que sabe onde estão as ferramentas. O Qwen 3 é como um mestre ceramista que te explica a química dos vidrados.

---

## 7. Embedding (Vetorização)

**O que é:** Transformar palavras ou conceitos em números que o computador pode comparar.

**Na cerâmica:** É como classificar as tuas peças por temperatura de cozedura. "Cone 6" e "1240°C" são descrições diferentes da mesma coisa.

**Na tecnologia:** O ANARI usa embeddings para encontrar documentos relacionados. Se pesquisares "vidrado", ele também encontra documentos sobre "esmalte", porque os embeddings são próximos.

---

## 8. MCP (Model Context Protocol)

**O que é:** Uma forma padronizada de ligar ferramentas a um modelo de IA.

**Na cerâmica:** É como ter uma tomada universal no teu atelier. Qualquer ferramenta (forno, torno, impressora) liga na mesma tomada.

**Na tecnologia:** O ANARI usa MCP para ligar o sistema de ficheiros, o Obsidian, o IPMA, e outras ferramentas. Todos "falam a mesma língua".

---

*Documento criado pela ANARI para os alunos do Manuel — 2026*

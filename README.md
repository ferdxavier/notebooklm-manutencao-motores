# 📚 Miniguia de Estudos & Curadoria: Motores Eletromagnéticos Universais (NotebookLM)

Repositório desenvolvido como parte do Desafio de Projeto da **DIO**, cujo objetivo principal é explorar o uso da Inteligência Artificial (especificamente o **Google NotebookLM**) como uma ferramenta de aprendizagem ativa, aliando pensamento crítico, curadoria de fontes e organização do conhecimento.

---

## 🎯 1. Contexto e Objetivos

* **Assunto de Interesse:** Estudo aprofundado sobre motores eletromagnéticos universais, com foco prático em análise técnica, diagnóstico de falhas, manutenção corretiva/preventiva e processos de reciclagem.
* **Objetivos de Estudo:**
  * Compreender o funcionamento interno, os princípios físicos e os componentes dos motores universais.
  * Dominar técnicas de manutenção técnica, testes com instrumentos (como o Megger) e identificação de defeitos comuns (curto-circuitos, desgaste de escovas, problemas no comutador, etc.).
  * Praticar a criação e estruturação de uma base de conhecimento personalizada utilizando o **Google NotebookLM** para acelerar o aprendizado técnico.

---

## 🔗 2. Curadoria de Fontes

Para alimentar o NotebookLM e garantir uma base de dados rica e diversificada (abrangendo teoria, prática de oficina e ferramentas de medição), foram selecionadas e cadastradas as seguintes fontes:

### Fontes de Vídeo (YouTube)
* [Vídeo 1 - Princípios e Funcionamento](https://www.youtube.com/watch?v=kjLdUMFDg2A)
* [Vídeo 2 - Análise Prática de Motores](https://www.youtube.com/watch?v=AWOomLa72mE)
* [Vídeo 3 - Processos de Manutenção](https://www.youtube.com/watch?v=Fa7Wkcrxhew)
* [Vídeo 4 - Diagnóstico e Reparos](https://www.youtube.com/watch?v=RdAtPCCi-h0)

### Fontes de Sites e Manuais
* [Manual / Referência sobre o uso do Megger em Medições](https://www.manualpdf.com.br/equipamentos-de-medi-o/megger)
* [Especificações e Equipamentos de Manutenção (Rebaixadora de Mica)](https://wfsites.websitecreatorprotool.com/hsdesenvolvimento.com.br/produtos/rebaixadora-de-mica)

### Fontes Locais (PDFs)
* *Arquivos locais adicionados ao caderno do NotebookLM contendo apostilas técnicas de rebobinagem, catálogos de motores e guias de segurança em manutenção elétrica.*

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta etapa, documentamos os testes realizados com a IA para extrair o máximo de precisão técnica do NotebookLM, bem como os desafios enfrentados:

* **Prompt Inicial (Muito Amplo):** 
  > *"Me explique como consertar um motor universal."*
  * **Dificuldade/Cicatriz:** A resposta gerada foi genérica demais, focando apenas em teoria básica e ignorando procedimentos específicos de oficina (como o rebaixamento de mica ou teste de isolamento com Megger).
* **Prompt Intermediário (Focado em Diagnóstico):** 
  > *"Com base nas fontes, quais são os principais sintomas de curto-circuito no induzido de um motor universal e quais ferramentas devo usar para testá-lo?"*
  * **Resultado:** Melhorou consideravelmente, trazendo menções ao uso do teste de continuidade e isolamento.
* **Prompt Final Otimizado (Diretrizes Técnicas Rígidas):**
  * *Ver seção de Prompts Reutilizáveis abaixo.*

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados
1. **O Motor Universal:** Caracteriza-se por funcionar tanto em corrente contínua (CC) quanto em corrente alternada (CA). É amplamente utilizado em eletrodomésticos e ferramentas portáteis (furadeiras, liquidificadores) devido ao seu alto torque de partida e rotação elevada.
2. **Componentes Críticos:** Estator (campo), rotor/induzido, comutador (coletor) e escovas de carvão. O desgaste mecânico e elétrico concentra-se majoritariamente no conjunto comutador/escovas.
3. **Manutenção e Diagnóstico:** 
   * O teste de isolamento com o **Megger** é vital para verificar fugas de corrente para a carcaça.
   * O rebaixamento do isolante de mica entre as lâminas do comutador utilizando uma **rebaixadora de mica** é um procedimento mecânico obrigatório após a usinagem (torneamento) do coletor para evitar curto-circuitos nas escovas.

### 🔤 Glossário Técnico
* **Comutador (Coletor):** Cilindro composto de lâminas de cobre isoladas entre si, conectado aos enrolamentos do induzido, responsável por inverter a polaridade da corrente nas bobinas.
* **Mica:** Material isolante natural posicionado entre as lamelas do comutador. Deve ficar ligeiramente abaixo do nível do cobre para não danificar as escovas.
* **Megger (Megômetro):** Instrumento de medição de alta resistência de isolamento elétrico.
* **Induzido (Rotor):** Parte girante do motor onde se localizam as espiras que interagem com o campo magnético do estator.

### 🛠️ Conjunto de Prompts Reutilizáveis
Guarde estes prompts para futuras consultas e revisões no seu NotebookLM:
* *Para diagnóstico de falhas:* `"A partir das fontes, liste um passo a passo de troubleshooting para um motor universal que não liga ou apresenta faiscamento excessivo nas escovas."`
* *Para processos específicos:* `"Explique detalhadamente qual é a função da rebaixadora de mica na manutenção do comutador e como o processo deve ser executado corretamente."`
* *Para testes de isolamento:* `"Quais são os critérios de segurança e os valores de referência esperados ao realizar um teste de isolamento utilizando o Megger nas fontes disponíveis?"`

---
Feito com 💻 e ⚡ para o ecossistema DIO.

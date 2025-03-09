## Planejamento Resumido

**Pré-pitch (28/03)**

- **Coleta e Preparação de Dados:** Identificar e coletar datasets públicos (imagens amadoras e imagens de produtos do site Tray).
- **Setup do Ambiente de ML:** Configurar o ambiente com Python e bibliotecas (TensorFlow ou PyTorch, OpenCV, etc.).
- **Prova de Conceito (POC):** Treinar um modelo base (ex.: ResNet50 pré-treinado) em um subconjunto dos dados para extrair embeddings e testar a similaridade.

**Entre Pré-pitch e Pitch 1 (28/03 a 11/04)**

- **Treinamento Inicial e Ajustes:** Refinar o modelo com técnicas de data augmentation e ajustar hiperparâmetros.
- **Avaliação:** Implementar métricas (como cosine similarity) para validar os embeddings.
- **Demo POC:** Preparar uma demo que mostre a extração dos embeddings e a comparação de imagens utilizando uma API simulada.

**Pós-Pitch 1 até Pitch 2 (11/04 a 06/06)**

- **Aprimoramento do Modelo:** Incorporar feedback do Pitch 1, melhorar o treinamento com mais dados e explorar técnicas avançadas (ex.: transfer learning, regularização).
- **Integração com Similaridade:** Integrar uma solução de indexação (ex.: FAISS) para busca rápida por similaridade.
- **Desenvolvimento da API de Inferência:** Criar uma API (com Flask ou FastAPI) para servir o modelo e integrá-la ao front-end.
- **Testes Finais e Otimizações:** Realizar testes de desempenho, corrigir bugs e otimizar o tempo de resposta.
- **Preparação da Demo Final:** Integrar todo o pipeline de AI na demo para o Pitch 2.

---

## Planejamento Semana a Semana

### Semana 1 (18/03 a 24/03)

- **Pesquisa de Dados:** Identificar e selecionar datasets públicos para imagens amadoras e de produtos.
- **Setup do Ambiente ML:** Configurar ambiente com Python, TensorFlow/PyTorch, OpenCV, etc.
- **Criação de Scripts de Pré-processamento:** Desenvolver scripts para limpeza e organização dos dados.

### Semana 2 (25/03 a 31/03)

- **Anotação e Preparação dos Dados:** Processar, anotar e organizar os datasets coletados.
- **Treinamento Inicial (POC):** Treinar um modelo base (ex.: ResNet50) em um subconjunto para extração de embeddings.
- **Experimentos Preliminares:** Testar a similaridade entre imagens e ajustar o pré-processamento.

### Semana 3 (01/04 a 07/04)

- **Refinamento do Treinamento:** Ajustar hiperparâmetros e aplicar técnicas de data augmentation.
- **Avaliação de Performance:** Implementar métricas de similaridade (cosine similarity) para validar os embeddings.
- **Preparação da Demo POC:** Consolidar uma demo inicial para exibir o funcionamento do modelo no Pitch 1.

### Semana 4 (08/04 a 14/04)

- **Pitch 1 e Feedback:** Apresentar a demo de AI no Pitch 1 (11/04) e coletar feedback específico.
- **Correções Imediatas:** Iniciar ajustes rápidos com base no retorno dos avaliadores.

### Semana 5 (15/04 a 21/04)

- **Aprimoramento do Modelo:** Continuar o fine-tuning com o conjunto completo de dados e testar variações na arquitetura.
- **Otimização do Pré-processamento:** Refatorar e melhorar o pipeline de pré-processamento.

### Semana 6 (22/04 a 28/04)

- **Integração de Similaridade:** Implementar integração com biblioteca de busca por similaridade (ex.: FAISS).
- **Testes Internos:** Validar a performance do modelo integrado ao mecanismo de similaridade.

### Semana 7 (29/04 a 05/05)

- **Desenvolvimento da API de Inferência:** Criar a API com Flask/FastAPI para servir o modelo.
- **Integração com Banco de Dados:** Iniciar testes de armazenamento dos embeddings dos produtos.

### Semana 8 (06/05 a 12/05)

- **Testes e Validação:** Realizar testes de inferência em diferentes cenários e dispositivos.
- **Refinamentos Adicionais:** Otimizar a API e ajustar o tempo de resposta.

### Semana 9 (13/05 a 19/05)

- **Sessões de Feedback:** Conduzir testes com usuários (internos/externos) para coletar novos insights.
- **Ajustes Baseados em Feedback:** Refinar a performance do modelo e da API conforme os insights.

### Semana 10 (20/05 a 26/05)

- **Preparação da Demo Final:** Consolidar melhorias e integrar a API com a aplicação final.
- **Testes Integrados:** Validar o fluxo completo entre AI e front-end.

### Semana 11 (27/05 a 02/06)

- **Ensaios e Documentação:** Realizar testes finais (QA), ensaios da demo e documentar o pipeline de AI.
- **Ajustes Finais:** Corrigir bugs e preparar materiais de apoio para o Pitch 2.

### Semana 12 (03/06 a 06/06)

- **Últimos Ajustes:** Correção de eventuais problemas de última hora e otimização final.
- **Preparação para Pitch 2:** Finalizar a integração e preparar a apresentação da demo completa.
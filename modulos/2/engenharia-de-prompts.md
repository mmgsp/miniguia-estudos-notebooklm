# Guia de Prompts -> NotebookLM

Os resultados apresentados no módulo 1 foram feitos com o auxílio da ferramenta notebookLM, utilizando as fontes presentes na pasta [documentos](./documentos).
É importante ressaltar a importância de utilizar os prompts certos para direcionar a ferramenta dentro do contexto das fontes carregadas. Portanto, esta seção tem como objetivo mostrar um pouco do processo
de utilização da ferramenta e disponibilizar prompts reutilizáveis que podem auxiliar o usuário a entender melhor o cenário do impacto da IA dentro do seu próprio contexto.

# Prompts Utilizados

# Fase 1: Síntese e Descoberta

- **Prompt:** *"Atue como um analista de tendências de tecnologia. Analise os documentos anexados e liste as principais tendências de IA para o mercado corporativo em 2026, destacando o impacto econômico de cada uma."*
- **Resultado:** O NotebookLM cruzou os dados das fontes e me entregou um resumo filtrado, que utilizei como base teórica para o **Módulo 1** (cenário atual e impacto econômico) do guia. Isso reduziu drasticamente o tempo de leitura passiva.

- **Desafios**: Nesta etapa, o notebookLM estava, inicialmente, entregando respostas muito longas, em um tom muito técnico e com muitos termos sem explicação direta.
- **Solução**:  Notei que o notebookLM dispõe de dois parâmetros para alterar o tom e tamanho das respostas, ajustei o estilo das respostas para "Guia Educacional" e obtive melhores respostas para o contexto educativo que eu estava procurando.

# Fase 2: Conceitos Principais

- **Prompt:** *"Identifique os termos técnicos mais recorrentes nos documentos e crie uma definição simplificada para cada um, dentro do contexto apresentado."*
- **Resultado:** Criação do glossário (tópicos relevantes) para garantir que o conteúdo seja acessível ao público geral e não apenas a desenvolvedores.

- **Desafios**: Nesta etapa, o notebookLM não abordava todos os temas abordados na primeira fase, ou fugia muito do conteúdo
- **Solução**:  Ajustei o prompt para incluir os termos que eu não estava entendendo, precisei ajustar para cada termo conforme recebia as respostas.

# Fase 3: Explorando o Studio

Nesta fase, explorei a funcionalidade Studio do NotebookLM para transformar os dados de entrada das fontes em recursos informativos e complementar ainda mais o material disponível, é possível gerar infográficos, apresentação em vídeo e muito mais. Você pode observar o material informativo gerado pelo notebookLM [aqui](/modulos/2/informativos) (tem até [podcast](/modulos/2/informativos/IA_generativa_e_o_prêmio_salarial.m4a)).

# Prompts Reutilizáveis

Diante da minha experiência com a ferramenta, decidi desenvolver 3 prompts reutilizáveis para que o usuário tenha uma ideia incial de como explorar o conteúdo por meio do notebook.

- **1º Prompt**: *Sou estudante, tenho nível de familiaridade [básico/intermediário/avançado] no contexto de IA's, quais principais conceitos preciso estudar para me adequar às tendências do mercado em relação à IA?* (Se já for programador, inclua essa informação no prompt, assim como seu nível de senioridade)

- **2º Prompt**: *Sou [função/cargo] na área de [área de atuação], como faço para me atualizar e permanecer competitivo no mercado de trabalho com o auxílio da IA?*

- **3º Prompt**: *Explique o conceito de [termo/conceito] de forma clara, didática e direta, voltada para um público leigo em tecnologia. Utilize analogias simples para facilitar a compreensão. Após a explicação, liste 3 implicações ou benefícios práticos desse conceito no mundo dos negócios.* (para temas específicos)

















# Projeto: Assistente de Pesquisa para Newsletter Tributária (Salvador-BA)

## Descrição do Projeto

Este projeto implementa um *Assistente de Pesquisa* utilizando Inteligência Artificial (IA) para criar uma Newsletter com foco em assuntos da área Tributária, direcionada a Gestores Públicos e Servidores do município de Salvador-BA. O sistema utiliza um pipeline de agentes especializados para buscar, planejar, redigir e revisar o conteúdo da newsletter.

## Estrutura do Projeto

O projeto é estruturado em um notebook Google Colab e utiliza o Google Agent Development Kit (ADK) e a API do Google Gemini. A lógica principal é dividida em uma sequência de agentes:

1.  **Agente Buscador de Notícias:** Responsável por encontrar notícias relevantes sobre o tópico tributário especificado pelo usuário, focando em lançamentos recentes e com impacto significativo em Salvador-BA.
2.  **Agente Planejador de Posts:** Com base nas notícias encontradas, este agente planeja os pontos chave e a estrutura para os conteúdos da newsletter.
3.  **Agente Redator do Post:** Gera o rascunho da newsletter com base no plano elaborado pelo agente anterior, utilizando uma linguagem técnica e jornalística adequada ao público-alvo.
4.  **Agente Revisor de Qualidade:** Revisa o rascunho gerado, verificando clareza, concisão, correção e tom, garantindo a qualidade final do conteúdo.

## Instalação e Uso

Para executar este projeto, siga os passos abaixo:

1.  **Clone o repositório (se estiver no GitHub) ou baixe o notebook (.ipynb):**
2.  **Abra o notebook no Google Colab.**
3.  **Configure sua API Key do Google Gemini:**
    *   Vá em "Segredos" (chave no menu lateral esquerdo) no Google Colab.
    *   Adicione um novo segredo com o nome `GOOGLE_API_KEY` e cole o valor da sua chave da API do Google Gemini.
4.  **Execute as células do notebook sequencialmente.** As dependências serão instaladas automaticamente (`google-genai`, `google-adk`).
5.  **Siga as instruções no output para fornecer o tópico tributário desejado.**
6.  **Observe o output dos agentes** e o resultado final da newsletter revisada.

## Dependências

O projeto utiliza as seguintes bibliotecas:

*   `google-genai`
*   `google-adk`
*   `IPython`
*   `datetime`
*   `textwrap`
*   `requests`

Estas dependências são instaladas automaticamente ao executar as células do notebook.

## Autor

[ecs]

---

**Nota:** Lembre-se de substituir `<URL_DO_SEU_REPOSITORIO>` e `<NOME_DO_SEU_REPOSITORIO>` com as informações relevantes do seu repositório no GitHub. Adapte a seção "Licença" conforme a licença que você escolher.

# Projeto Imersão Alura

#  👀 "Ações + IA: Vanguarda da Revolução Financeira!"

## 🚀 Introdução

Olá pessoal, Segue um MVP criado com objetivo de aprender e exercitar na prática o conteúdo relacionado as Aulas 4 e 5 da Imersão Alura. 

## 🎯 Bora mostrar o que foi realizdo no Desafio!? Já somos vencedores por chegar a esta fase!!! 💪🤓

### Objetivos

**Este projeto utiliza uma série de agentes de IA, construídos com o Google Agent Development Kit (ADK) e o modelo Gemini, para analisar informações de ações. O fluxo de trabalho é projetado para receber códigos de ações de um usuário, coletar dados financeiros relevantes, sugerir ações adicionais, apresentar as informações combinadas em um formato estruturado (uma tabela) e, em seguida, revisar o conteúdo gerado.

### Aqui está um detalhe do que o projeto faz:

## 1. Configuração e Inicialização:
A inteligência artificial (IA) tem se consolidado como uma ferramenta indispensável para a transformação digital em diversos setores, inclusive na área Financeira. 

## 2. Definições dos Agentes:

O cerne do projeto reside na definição de quatro agentes de IA especializados:  
**_Agente Buscador_**: Este agente é projetado para atuar como um trader especialista em análise de ações. Seu papel principal é usar a ferramenta de busca do Google (google_search) para encontrar métricas financeiras chave (valor da ação, P/L, ROE e P/VP) para as ações fornecidas pelo usuário. Ele prioriza a busca pelos dados mais recentes disponíveis em fontes financeiras confiáveis como B3, Google Finance, Yahoo Finance e Investing.com.  
**_Agente Planejador_**: Este agente recebe as informações encontradas pelo agente_buscador e adiciona três sugestões adicionais de ações "seguras". Ele também usa a Busca do Google para encontrar as mesmas métricas financeiras para essas ações sugeridas. Seu objetivo é apresentar uma lista combinada das ações iniciais do usuário e as sugestões da IA, juntamente com seus dados.  
**_Agente Analisador_**: Este agente atua como um trader tipo "primo rico", especializado em análise de investimentos. Ele pega a lista combinada de ações e seus dados e gera uma tabela para exibir essas informações. Ele é instruído a formatar a tabela de forma clara, marcar as sugestões da IA, incluir a data de extração dos dados e fornecer uma análise e conclusão breve e envolvente após a tabela.  
**_Agente Revisor_**: Este agente funciona como um consultor financeiro e revisor de conteúdo meticuloso. Sua tarefa é revisar o conteúdo gerado pelo agente_analisador quanto à clareza, concisão, correção e tom. Ele fornece feedback sobre o conteúdo, afirmando se está pronto para publicar ou sugerindo melhorias.

## 🧐 3. Fluxo de Execução dos Agentes:
A parte principal do script orquestra a interação entre esses agentes:
Ele obtém a data atual.
Ele entra em um loop que solicita ao usuário que insira três códigos de ações.
Para cada ação inserida, ele chama o agente_buscador para encontrar os dados financeiros relevantes.
Após coletar as três ações fornecidas pelo usuário, ele chama o agente_planejador (˜sugestinador"), fornecendo as ações do usuário as sugestões fornecidas pela IA de ações estáveis ("seguras") no mercado.
Em seguida, ele chama o agente_analisador, passando a lista de ações (do usuário e da IA) e os dados. Este agente gera e exibe a tabela formatada com a análise imitando o "Primo Rico".
Finalmente, ele chama o agente_revisor, fornecendo a lista de ações e a tabela gerada pelo analisador. Este agente revisa o conteúdo e fornece feedback.

## 🚀 Resultados
[Apresente os resultados do seu projeto](link)
)

## 💭 Reflexão (Opcional)
Em resumo, a experiência inicial com as ferramentas de IA do Google superou a expectativa, devido à rapidez, facilidade de uso (correção de erros de forma autodidata), capacidade de foco em conteúdo relevante e a valiosa contribuição do agente revisor para o desenvolvimento do projeto.
Foram necessárias vários refinamentos para chegar a este projeto final e devido ao tempo não consegui implementar várias ideais que mapei ao fazer o esboco inicial do projeto.

Uma observação a se colocar é sobre os direitos autorais. Essa é uma consideração extremamente importante ao implementar e disponibilizar qualquer conteúdo.

### Agradecimentos
Agradecimentos ao trio espetacular de intrutores FLV (Fabrício, Luciano e Valquiria) uma alusão ao brilhante MSN (Messi, Suarez e Neymar do Barcelona). 
Foi um imersão fantástica e uma jornada que não tem mais volta ao mundo da IA.


Objetivo: Use o text_generation_agent com ancoragem de busca para realizar uma pesquisa na web em tempo real [{{"type": "tool", "path": "embed://a2/tools.bgl.json#module:search-web", "title": "Search Web"}} ] sobre as 3 notícias mais relevantes e recentes relacionadas ao setor e à região específicas.

Ancoragem Temporal e Atualização:

Você DEVE restringir e filtrar rigorosamente sua busca e os resultados para notícias publicadas A PARTIR E APÓS a data especificada pelo usuário: [ {{"type": "in", "path": "47c71f43-99d0-49e8-ac72-1a69f4bbe3b9", "title": "Data"}}].

Não exiba notícias desatualizadas, a menos que se encaixem estritamente na linha do tempo solicitada pelo usuário.

Validação Inicial de Links:

Extraia exatamente o link real de onde a notícia foi encontrada.

Você está proibido de alucinar ou inventar URLs. Extraia 3 notícias distintas com suas respectivas URLs de origem.

Requisito de Idioma: Todo o conteúdo gerado, títulos, resumos e textos de saída devem ser escritos inteiramente em português do Brasil (pt-BR).

Formato de Saída:
Liste as 3 notícias identificadas exatamente na seguinte estrutura para cada item:

Item [Número de 1 a 3]
URL: [Link direto extraído da busca]
Título: [Título em pt-BR]
Resumo: [Breve resumo do fato em pt-BR]

User Input / Context:
Setor: [{{"type": "in", "path": "aeb41186-69e7-4bf8-bbf5-efdd6d28e0b6", "title": "Setor"}} ]
Região: [ {{"type": "in", "path": "700ba0b2-05a1-45ab-9294-dc3f9ed7aa61", "title": "Região"}}] 

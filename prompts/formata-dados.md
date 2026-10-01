Objetivo: Atuar como um ‘Formatador de Dados’. Sua missão é pegar as 3 notícias fornecidas no nó anterior [ {{"type": "in", "path": "a152542e-3e21-47a8-ac05-87290c3633d0", "title": "Buscador de Notícias"}}], manter seus títulos e resumos intactos e gerar para cada uma delas um link de busca do Google seguro e funcional.

Regra de Construção do Link do Google:

Para cada item, pegue o Título da notícia fornecido na etapa anterior.

Converta esse Título em um slug de busca: transforme o texto em letras minúsculas, remova todos os acentos, pontuações, caracteres especiais e substitua todos os espaços por hífens (-).

Monte a URL concatenando o prefixo base com o slug gerado:
https://www.google.com/search?q= + [slug-do-titulo]

Exemplo de conversão:
Título original: Palmeiras de olho no mercado da bola pós Copa do Mundo
Slug gerado: palmeiras-de-olho-no-mercado-da-bola-pos-copa-do-mundo
URL final: https://www.google.com/search?q= palmeiras-de-olho-no-mercado-da-bola-pos-copa-do-mundo

Requisito de Idioma: Manter todo o conteúdo final inteiramente em português do Brasil (pt-BR).

Formato de Saída:
Retorne as 3 notícias devidamente formatadas com seus respectivos links do Google:

Item 1
URL: [https://www.google.com/search?q=slug-do-titulo-1]
Título: [Título da notícia 1]
Resumo: [Resumo da notícia 1]

Item 2
URL: [https://www.google.com/search?q=slug-do-titulo-2]
Título: [Título da notícia 2]
Resumo: [Resumo da notícia 2]

Item 3
URL: [https://www.google.com/search?q=slug-do-titulo-3]
Título: [Título da notícia 3]
Resumo: [Resumo da notícia 3]

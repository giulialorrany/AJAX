# Consulta de CEP com Diferentes Métodos de AJAX

Disciplina: Linguagem de Programação Web I  
Professor: Márcio Araya  
Aluno: Giulia Lorrany
Turma: 2º matutino, ADS  
Data: 24/05/2026

# Introdução

Nessa atividade eu explorei diferentes formas de fazer requisições assíncronas (AJAX) no JavaScript. Peguei o exemplo original mostrado em sala (`ajax3.html`) e recriei ele usando **Fetch**, **Promises** e **Async/Await**.

O objetivo foi entender na prática as diferenças entre os métodos, principalmente em relação à facilidade de escrita e manutenção do código.

# 1. Comparação entre os Métodos

Depois de pesquisar e testar os códigos, fiz essa tabela comparativa:

| Método                  | Ano    | Dificuldade | Legibilidade | Tratamento de Erros     | Minha Opinião Pessoal                     |
|-------------------------|--------|-------------|--------------|--------------------------|-------------------------------------------|
| XMLHttpRequest         | 1999   | Alta        | Ruim         | Complicado               | Muito antigo e verboso                    |
| Fetch API              | 2015   | Baixa       | Boa          | Médio                    | Bom, mas ainda um pouco verboso           |
| Promises (.then)       | 2015   | Média       | Razoável     | Com .catch()             | Melhor que XHR, mas pode ficar confuso    |
| Async/Await            | 2017   | Muito Baixa | Excelente    | Com try/catch            | **Meu favorito!** Código bem mais limpo   |

Conclusão pessoal:
O `async/await` ganhou de facilmente pra mim. O código fica muito mais fácil de ler e entender, parece código síncrono. O `XMLHttpRequest` é bem mais trabalhoso. Em termos de desempenho, não senti diferença significativa — o que mais importa é a conexão com a internet.

# 2. Arquivos Criados

- `original-xhr.html` → Versão original da aula (XMLHttpRequest)
- `fetch.html` → Usando Fetch API
- `promises.html` → Usando Promises com `.then()`
- `async-await.html` → Usando Async/Await (minha versão preferida)

# 3. O que eu aprendi

- Entendi melhor o conceito de assincronismo no JavaScript
- Vi a evolução das técnicas ao longo dos anos
- Percebi que código limpo e legível é tão importante quanto fazer o programa funcionar
- Async/Await é atualmente a melhor forma de escrever código assíncrono

Gostei bastante da atividade! Foi bem prático ver as diferenças na hora de codar.

Qualquer dúvida, pode falar comigo!

# **Análise de Sentimentos com Language Studio no Azure AI**
Exploramos o Azure AI: análise de textos (idioma, sentimento, palavras-chave e entidades), bot (funcionamento e testes) e linguagem coloquial (enunciado, entidade e intenção). No Estúdio de Fala, testamos transcrição, tradução e legendagem, e no Language Studio classificamos sentimentos e opiniões.

**As setenças de teste para classificar o sentimento forám**: 
- 1.A reunião começou pontualmente às 10h
- 2.Estou radiante com os resultados incríveis do projeto.
- 3.Sinto-me desapontado e triste com os acontecimentos de hoje.
  
  obs(os prints dos resultados de cada uma está na pasta prints com sua devida númeração)

  **Insights**
  - Na primeira sentença, ele classificou corretamente como sentimento neutro, apesar de ter 2% para um sentimento positivo e 1% para negativo.

  - Na segunda sentença, ele novamente classificou corretamente como sentimento positivo, tanto que foi 100%
    
  - Na terceira e última sentença, ele classificou corretamente como sentimento negativo com 100%.
    
  Consideração final: ele teve um ótimo desempenho em todas as sentenças, apenas com um pouco de dúvida na primeira, mas ainda assim conseguindo classificá-la corretamente.

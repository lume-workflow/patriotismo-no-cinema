# 🇺🇸 Estrelas da Pátria: A Popularidade dos Filmes Patrióticos ao Longo da História

Este projeto analisa 100 filmes com temática patriótica usando dados reais da TMDb API, com foco em compreender como **momentos históricos** (como guerras, crises ou estabilidade política) influenciam a **popularidade e avaliação pública** dessas produções.
---

## 📌 Conclusão

🟢 Filmes patrióticos não são mais populares em tempos de guerra — e sim em tempos de paz. <br>
🟡 Uma análise de 100 filmes com temática patriótica, usando dados da TMDb, mostrou que os lançamentos com maior popularidade média ocorreram em períodos de estabilidade nacional ou de tensão política interna — não em momentos de guerra real ou crise externa.<br>
🟣 Esse padrão revela uma possível função simbólica do cinema patriótico: reforçar identidades nacionais em tempos de calmaria ou disputas ideológicas, mais do que apenas servir como resposta emocional em momentos de conflito armado. <br>

Em resumo: o patriotismo nas telas parece florescer quando as nações estão tentando se lembrar de quem são — não apenas quando estão lutando contra inimigos externos.

---

## 🖼️ Visualização principal

![Gráfico: Popularidade média por contexto histórico](grafico-popularidade-e-contexto.png)

---

## 📌 Objetivo

Investigar se há relação entre o **momento histórico de lançamento** e a **popularidade ou nota média** dos filmes patrióticos.

---

## 🔍 Perguntas orientadoras

- Filmes patrióticos são mais populares durante guerras ou períodos de estabilidade?
- A polarização política interna influencia o engajamento com filmes patrióticos?
- O contexto histórico afeta a avaliação crítica (nota média) desses filmes?

---

## 🛠️ Tecnologias utilizadas

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebooks
- API da The Movie Database (TMDb)

---

## 📊 Principais descobertas

- 🎯 **Filmes lançados em períodos estáveis ou de polarização política interna** apresentaram **as maiores médias de popularidade.**
- ⚔️ **Filmes lançados durante guerras reais (como Vietnã ou Segunda Guerra Mundial)** tiveram **popularidade média significativamente menor.**
- ⭐️ **As notas médias dos filmes permaneceram estáveis** entre os diferentes contextos históricos, sugerindo que **popularidade e avaliação crítica são fenômenos distintos.**
- ❗️ O filme *Oppenheimer* foi tratado como **outlier**, devido à sua popularidade atípica.
- 🧠 **Filmes patrióticos parecem ganhar mais força em momentos de busca por identidade nacional** — seja em tempos de estabilidade, polarização interna ou incerteza política — do que em guerras propriamente ditas.

---

## 🔐 Como configurar sua chave da TMDb

Este projeto usa a API do The Movie Database (TMDb), que exige uma chave para acessar os dados.

1. Crie uma conta gratuita em [TMDb](https://www.themoviedb.org/)
2. Vá até [Configurações > API](https://www.themoviedb.org/settings/api) e gere sua chave (v3)
3. Crie um arquivo chamado `.env` na raiz do projeto com o seguinte conteúdo:
TMDB_API_KEY=sua_chave_aqui


## 📎 Fonte de dados

- [TMDb API](https://www.themoviedb.org/documentation/api)

---

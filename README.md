# Max PF Ranking

Página única (HTML + JavaScript, sem build) que mostra, para cada liga sua no Sleeper, onde você está entre os melhores e quantos pontos está deixando no banco: pontos feitos (PF) comparados com o máximo possível (Max PF).

## Como usar

Abra o `index.html` no navegador (ou publique pelo GitHub Pages), digite seu username ou user_id do Sleeper e clique em **Carregar**. **Atualizar** busca os dados de novo.

Clique numa liga para ver a tabela de todos os times.

## Observações

- Usa só a API pública do Sleeper (`api.sleeper.app/v1`); não precisa de login.
- A página tenta guardar o último resultado com `window.storage`, que só existe dentro dos artifacts do Claude. Fora dele essa etapa é ignorada sem erro e os dados são buscados de novo a cada carregamento.

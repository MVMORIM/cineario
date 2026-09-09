# CINEÁRIO

Biblioteca pessoal de filmes e séries — com progresso, avaliações e diário.

## Como publicar no GitHub Pages

1. Suba estes arquivos para a raiz do seu repositório.
2. Vá em **Settings → Pages**.
3. Em "Branch", selecione `main` e a pasta `/ (root)`.
4. Salve. Em alguns minutos seu app estará em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPO/`

## Como funciona

- Os dados ficam salvos no navegador de cada visitante (IndexedDB/localStorage).
- Na primeira vez que alguém abrir o site sem dados salvos, o app carrega
  automaticamente o arquivo `cineario_backup_2026-09-09T14-59-14.json` como
  ponto de partida (seus 80 títulos já cadastrados).
- Depois disso, qualquer edição fica salva localmente naquele navegador.
- Use o botão de **exportar backup** dentro do app para gerar um novo
  arquivo `.json` sempre que quiser salvar uma cópia atualizada.

## Arquivos

- `index.html` — o app completo (HTML + CSS + JS).
- `cineario_backup_2026-09-09T14-59-14.json` — backup inicial com os títulos.

# Portfólio Digital - Pércia Mabota

Este repositório contém um portfólio estático pronto para ser publicado no GitHub Pages.

Estrutura principal:

- `index.html` — página principal (menu e iframes para as outras páginas)
- `formulario.html` — formulário de evento
- `galeria.html` — galeria de imagens, áudio e vídeo
- `cv.html` — currículo digital
- `imagens/`, `videos/`, `audios/` — pastas para os assets (adicione os ficheiros aqui)

Publicar no GitHub Pages (resumo):

1. Crie um repositório no GitHub e envie todo o conteúdo desta pasta para ele.
2. Nas configurações do repositório, ative GitHub Pages apontando para a branch `main` (ou `master`) e a pasta `/` (root).
3. Aguarde alguns minutos — o site estará disponível em `https://<seu-usuario>.github.io/<seu-repo>/`.

Exemplo rápido (PowerShell) — já com repositório criado e inicializado localmente:

```powershell
# dentro da pasta do projeto
git init
git add .
git commit -m "site inicial"
git branch -M main
git remote add origin https://github.com/<usuario>/<repo>.git
git push -u origin main
```

Observações:
- Substitua `<usuario>` e `<repo>` pelos seus dados.
- Coloque os ficheiros de imagem, áudio e vídeo nas pastas `imagens/`, `audios/`, `videos/` antes de publicar para que a galeria funcione offline.
- Se preferir URLs sem nomes longos, eu posso renomear os ficheiros e atualizar os links automaticamente.

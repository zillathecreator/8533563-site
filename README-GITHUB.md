# Snapshot estático de 8533563.com

Este pacote foi montado a partir dos recursos do site presentes no arquivo HAR.

## Estrutura

- `index.html` — página inicial
- `css/` — folhas de estilo
- `js/` — JavaScript
- `img/`, `png/`, `avif/` — imagens e recursos
- `theme/` — tema
- `sw-path.json` — configuração capturada

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Confirme o commit na branch `main`.
4. Vá em Settings → Pages.
5. Em Build and deployment, selecione `Deploy from a branch`.
6. Escolha `main` e `/ (root)`.
7. Salve.

## Importante

O HAR também contém chamadas de API e serviços externos. Elas não foram transformadas em arquivos estáticos neste pacote. Portanto, o site pode abrir visualmente, mas funcionalidades que dependem do backend/API original podem não funcionar no GitHub Pages.

Não coloque credenciais, tokens ou arquivos `.env` em um repositório público.

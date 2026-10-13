# Código da Dor · Corpo Primaz

App demo gratuito do Corpo Primaz: triagem, pop-up de segurança, 3 testes de movimento com vídeo em loop, captura de contato e resultado com plano de 7 dias.

Site estático, sem build e sem dependências. Abra o `index.html` ou publique a pasta como está.

## Estrutura
- `index.html`: o app inteiro (HTML, CSS e JS)
- `assets/`: símbolo, foto do Douglas, vídeos e capas dos testes

## Publicar no GitHub Pages
1. Suba esta pasta para um repositório.
2. Abra Settings, depois Pages, e escolha Deploy from a branch: `main`, pasta `/ (root)`.
3. O endereço fica `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Antes de ir para produção
- `LINK_DESPERTAR` no `index.html` ainda é `#despertar`. Trocar pelo link real do checkout.
- Os dados do formulário ficam só no navegador da pessoa (localStorage). Para receber os leads é preciso ligar a um formulário: Netlify Forms, Hotmart ou uma planilha via webhook.

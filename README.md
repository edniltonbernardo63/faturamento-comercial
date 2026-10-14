# Painel Pet Voyage — demonstração

Painel de faturamento com login, gráfico de serviços, ranking de vendedoras e metas.
**Todos os dados são fictícios** e tudo roda no navegador: não existe servidor, planilha nem senha real.

## Como testar
- Entre com `demo@exemplo.com` e a senha `demo12345`.
- Ou crie um cadastro com um dos nomes liberados: **Ana Souza**, **Bruno Lima** ou **Carla Mendes**.
  Qualquer outro nome é recusado, como na versão real.
- Meses disponíveis no calendário: agosto, setembro e outubro de 2026.

## Publicar no GitHub Pages
1. Crie um repositório e envie o arquivo `index.html`.
2. No repositório: **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`. O link fica `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Diferenças para a versão real
- A versão real lê a planilha do Google e cadastra pessoas numa planilha de controle, usando Apps Script.
- Aqui, o "servidor" é um script dentro do próprio `index.html` e os cadastros ficam só no navegador de quem testa.
- A cor é violeta, para não confundir com o painel real.

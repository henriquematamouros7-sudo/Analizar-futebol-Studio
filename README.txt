FUTEBOL STUDIO — CADERNO VIP
================================
Versão 1.0.0


O QUE É
-------
Um caderno digital pessoal (PWA) para registrar, organizar e estudar suas
análises: cartas altas, cartas baixas, empates, padrões, estratégias e
sessões de estudo. Este é um projeto novo e independente — não altera nem
depende do seu outro aplicativo "Futebol Studio Pro".

Todos os dados ficam salvos apenas neste dispositivo (localStorage do
navegador, chave "futebol_studio_caderno_v1"). Não há backend, não há
login, não há coleta de dados. Depois de carregado uma vez, o app
funciona offline.


ARQUIVOS ENTREGUES
-------------------
index.html            -> aplicativo completo (HTML + CSS + JS)
manifest.webmanifest   -> manifesto do PWA
sw.js                  -> service worker (cache offline)
icon-192.png            -> ícone do app (192x192)
icon-512.png            -> ícone do app (512x512)
README.txt              -> este arquivo


COMO PUBLICAR NO GITHUB PAGES
------------------------------
1. Crie um novo repositório no GitHub (ex: futebol-studio-caderno-vip).
2. Envie estes 5 arquivos para a raiz do repositório, mantendo os nomes
   exatamente como estão (o arquivo principal precisa se chamar
   "index.html").
3. No repositório, vá em Settings > Pages.
4. Em "Branch", selecione a branch principal (main) e a pasta raiz "/ (root)".
5. Salve. O GitHub vai gerar uma URL pública (algo como
   https://seu-usuario.github.io/futebol-studio-caderno-vip/).
6. Abra essa URL no iPhone pelo Safari.


COMO INSTALAR NA TELA INICIAL DO IPHONE
-----------------------------------------
1. Abra a URL do app no Safari.
2. Toque no ícone de compartilhar (quadrado com seta para cima).
3. Escolha "Adicionar à Tela de Início".
4. O app abrirá em tela cheia, como um aplicativo nativo.


PRINCIPAIS FUNCIONALIDADES
----------------------------
- Dashboard "Meu Caderno" com estatísticas rápidas e últimas anotações.
- Cadernos: Cartas Altas, Cartas Baixas, Empates, Análise de Padrões,
  Estratégias, Estudos, Diário de Sessões e Favoritos.
- Nova Anotação com título, categoria, data/hora automáticas, contexto,
  sequência observada, análise, hipótese, resultado, lições, observações
  e tags (sugeridas + personalizadas).
- Biblioteca de Padrões com grau de confiança (Baixo / Médio / Alto) e
  aviso de que padrões são registros de estudo, não garantias.
- Estratégias com status (Em estudo / Testando / Aprovada para estudo /
  Arquivada) e aviso de que não representam garantia de lucro.
- Diário de Sessões com nota de 1 a 10 e campos de autoavaliação.
- Busca global em títulos, textos, categorias, tags, padrões, estratégias
  e observações.
- Filtros por período (hoje / 7 dias / 30 dias / todos), favoritos e tags.
- Favoritar (⭐) e Fixar (📌) anotações.
- Estatísticas com distribuição por categoria e atividade dos últimos
  7 dias.
- Backup: exportar caderno completo, exportar apenas anotações ou
  exportar tudo em JSON; importar backup com confirmação (nunca apaga
  dados existentes sem confirmação).
- 3 temas: Obsidian Premium (preto + dourado), Midnight (preto + azul)
  e Emerald (preto + verde).
- Navegação inferior fixa: Início, Cadernos, Nova, Buscar, Mais.
- Confirmação obrigatória antes de excluir qualquer item, e confirmação
  dupla antes de limpar todos os dados.
- Instalável como PWA, com funcionamento offline após o primeiro
  carregamento.


IMPORTANTE
----------
Este aplicativo tem finalidade de registro, organização e estudo pessoal.
Ele não afirma que padrões garantem resultados futuros e não apresenta
estratégias como garantia de lucro — todo o conteúdo é tratado como
observação histórica e material de estudo.


SUPORTE / MANUTENÇÃO
----------------------
O código está todo em um único arquivo index.html (HTML, CSS e
JavaScript), organizado em seções comentadas, para facilitar ajustes
futuros. Os dados de cada usuário nunca saem do próprio dispositivo.

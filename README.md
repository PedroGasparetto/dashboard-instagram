# Dashboards de Performance — Redes Sociais

Relatórios mensais em página única (HTML, CSS e JS puros — sem dependências, sem build).
Há dois painéis, com um botão no topo para alternar entre eles:

- **Instagram** (paleta laranja): https://pedrogasparetto.github.io/dashboard-instagram/
- **LinkedIn** (paleta azul): https://pedrogasparetto.github.io/dashboard-instagram/linkedin.html

## O que tem

- **Comparativo mensal** — gráficos de rosca comparando dois meses escolhidos nos seletores do topo, com a variação percentual entre eles.
  - Instagram: curtidas, compartilhamentos, visualizações, novos seguidores e contas alcançadas.
  - LinkedIn: impressões, comentários, compartilhamentos, seguidores e visualizações.
- **Evolução mensal** — gráficos de barras com todos os meses cadastrados (no LinkedIn, as interações somam comentários + compartilhamentos).
- **Formulário de inserção** — botão "＋ Inserir dados" abre o painel lateral para cadastrar, editar, reordenar ou excluir meses.
- **Exportar / importar JSON** — para levar os dados de um navegador para outro ou guardar uma cópia.
- **Tema claro e escuro** e layout responsivo.

## Onde os dados ficam

Tudo é salvo no `localStorage` do navegador de quem acessa. Nada é enviado para servidor
algum e nenhum número fica no repositório — a página publicada abre com os meses zerados.
Limpar os dados do navegador apaga o que foi cadastrado, então use o **Exportar JSON**
para manter um backup.

## Sobre a senha

A tela de acesso é uma trava de visualização, não segurança de verdade: a validação roda
no navegador e qualquer pessoa com acesso ao código-fonte consegue contorná-la. Serve para
evitar exibição acidental do relatório — não use para proteger informação sigilosa.

## Uso local

Basta abrir o `index.html` no navegador. Não precisa de servidor.

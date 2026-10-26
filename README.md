# Forma Studio 5.0 — Mapa panorâmico

Editor visual de planejamento para um **marketplace de missões físicas**, com visualização horizontal e navegação rápida entre áreas.

## Preview

https://enzoco2612-png.github.io/forma-studio/

A publicação é feita pelo GitHub Pages na branch `main`. Após o deploy, use Ctrl + Shift + R caso o navegador ainda mostre a versão anterior.

## O que mudou na versão 5.0

- **Mapa horizontal em quatro etapas**, com cinco grupos lado a lado na primeira etapa e ramificações em **duas colunas**, evitando o formato de “pilastra” vertical.
- **14 grupos estratégicos** preservados e acessíveis pelos botões de navegação acima do canvas.
- **Minimapa interativo** no canto inferior direito: clique ou arraste para mover a visualização.
- **Visão geral** com enquadramento de todo o mapa.
- **Rolagem horizontal** segurando Shift com o scroll ou usando o deslocamento lateral do touchpad.
- **Teclas de seta** para navegar; Shift + seta move mais rápido; Home enquadra tudo.
- Os cartões da Visão 360 continuam abrindo diretamente as áreas correspondentes do mapa.
- Melhor uso da largura em telas grandes, incluindo cartões do painel estratégico em quatro colunas quando houver espaço.
- Correção de uma inconsistência anterior: o editor agora **lê e grava na mesma chave de salvamento, v5**, com migração do mapa estratégico v4 quando existir.

## Estrutura preservada

O modelo atual está em `nossa-missao-corrigida.json` e incorporado a `index.html`.

Há **14 pilares, 145 pontos de planejamento, 4 agrupadores de etapas e 1 nó central**, totalizando **164 blocos e 163 conexões**. O conteúdo das ideias foi preservado: a atualização reorganiza os blocos em um panorama mais amplo.

Os backups anteriores continuam no repositório:

- `backups/nossa-missao-original.json`: mapa antigo de 72 blocos.
- `backups/nossa-missao-estrategia-360-vertical.json`: Estratégia 360 antes da reorganização horizontal.

## Funções do editor

Edição dos textos, duplicação, criação de blocos e ramificações, conexões curvas coloridas, busca, status, prioridade, tema claro/escuro, zoom, organização automática, importação JSON e exportação JSON/SVG/PNG.

**Armazenamento:** as alterações feitas dentro do editor são salvas somente no `localStorage` do navegador. Não há sincronização em nuvem. Exportar o JSON periodicamente continua sendo importante. O GitHub guarda o código e o mapa inicial, mas não atualiza automaticamente com as suas edições locais.

## Uso responsável

As categorias, propostas e métricas do marketplace são hipóteses de produto para validação em uma região piloto. Serviços, pagamentos, reputação, proteção de dados e regras de segurança devem ser operacionalizados e verificados antes do lançamento comercial.

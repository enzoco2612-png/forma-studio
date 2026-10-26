# Forma Studio 4.0 — Estratégia 360

Editor estratégico para desenvolver um **marketplace de missões físicas e serviços locais**. O foco do produto é conectar pessoas que precisam resolver pequenas tarefas presenciais a executores locais disponíveis.

## Preview

https://enzoco2612-png.github.io/forma-studio/

**Como navegar:** o sistema abre na **Visão estratégica 360**, com cartões de áreas do negócio. Clique em um cartão para visualizar o grupo e suas ramificações no mapa mental. Use o botão **✦ Visão 360** para voltar ao painel.

## Estrutura do planejamento

- **14 pilares estratégicos** com cores próprias.
- **145 pontos de estudo, decisão ou experimentação**.
- **160 blocos e 159 conexões** na versão inicial do mapa.
- Grupos: Proposta de valor; Contratantes; Executores; Catálogo de missões; Dores e ângulos; Aquisição de clientes; Aquisição de executores; Funis; Experiência do produto; Segurança e confiança; Monetização; Retenção; Métricas; Roadmap.
- Categorias e posicionamentos são **hipóteses de estratégia**, não resultados comprovados de mercado.

## Prioridade recomendada

1. **Validação em bairro piloto:** entrevistar contratantes e executores, identificar quais missões têm demanda e executar testes reais.
2. **Liquidez e confiança:** verificação de identidade, regras de categorias permitidas, preço transparente, suporte, solução de conflitos e acompanhamento do serviço.
3. **Aquisição e crescimento:** tráfego geolocalizado, funis separados para demanda e oferta, indicações e parcerias, medindo a margem por categoria antes da expansão.

## Editor

- Criação, edição e duplicação de blocos; ramificações; ligações curvas.
- Zoom, enquadramento, foco por área e organização automática.
- Filtro de áreas no dashboard, busca de ideias, destaque por cores.
- Edição de **status** (Ideia, Em teste, Validado) e **prioridade** (Alta, Média, Baixa).
- Importação/exportação em JSON; exportação em SVG e PNG.
- Modos escuro/claro; atalhos.

## Preservação do planejamento antigo

- `backups/nossa-missao-original.json` mantém sua estrutura de **72 blocos e 71 conexões**.
- O botão **Original · 72 blocos** carrega exatamente essa cópia.
- O botão **Recuperar mapa anterior** tenta ler uma versão anterior salva no navegador e, se não existir, abre o backup original.
- A nova estrutura está em `nossa-missao-corrigida.json` e dentro de `index.html`.

### Atenção: salvamento local

A interface usa **localStorage** para guardar alterações, não uma base de dados online. Editar no navegador **não atualiza o repositório GitHub**. Use **Exportar JSON** para guardar um backup e **Importar** para recuperar. Quando a versão do editor é atualizada, dados de versões antigas continuam no navegador, mas não são sincronizados entre aparelhos. Uma base de dados na nuvem precisa ser implementada separadamente.

## Inspirações para validar (não são integrações implementadas)

- [Taskrabbit — confiança e segurança](https://support.taskrabbit.com/hc/en-us/articles/46260491906203-Overview-of-Trust-and-Safety): verificação de prestadores e resolução de disputas.
- [Taskrabbit — experiência do serviço](https://www.taskrabbit.com/how-it-works): contratação, precificação e suporte.
- [Stripe Connect](https://stripe.com/en-br/connect/features): modelos possíveis de pagamentos e repasses para marketplaces.

Nenhum processamento de pagamentos, verificação de identidade ou integração com essas plataformas está implementado neste editor. As normas aplicáveis, atividades permitidas, políticas de privacidade e questões trabalhistas devem ser avaliadas antes do lançamento do marketplace.

## Publicação

O repositório usa GitHub Pages a partir da branch `main` e da pasta `/(root)`. Alterações no `index.html` são publicadas pelo serviço quando a implantação termina.

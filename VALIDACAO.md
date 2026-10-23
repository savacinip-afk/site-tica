# Validação — versão 2.0 — 23/10/2026

Ambiente real: WordPress 6.8, PHP 8.3 via WordPress Playground, SQLite e Chromium 153. Demonstração local, sem publicação na Hostinger.

Verificado:
- Instalação e inicialização locais, com reinicialização do processo.
- Sete páginas com HTTP 200 e conteúdo renderizado sem erros PHP detectados.
- Cinco unidades e seis artigos educativos na demonstração.
- Formulário em etapas, campos obrigatórios, telefone inválido e consentimento.
- Pré-seleção por URL e cartão, sem conflito com a rota Unidade.
- Revisão com texto seguro, mensagem com acentos codificada e destino conforme seleção.
- Envio bloqueado sem WhatsApp válido na unidade; nenhuma mensagem real foi enviada.
- Mapa só criado após clique.
- Filtros de categorias e cidades com número correto de resultados e estado acessível.
- Janela de produto com imagem real, descrição, chamada de contato, foco interno, fechamento por Escape e retorno do foco ao botão de origem.
- Imagens de referência locais carregadas e preenchendo os cards.
- Revelação de seções durante a rolagem, progresso de leitura e cabeçalho fixo.
- Larguras de 360, 390, 768 e 1440px sem transbordamento horizontal.
- Menu móvel e preferência de movimento reduzido (animações desativadas e conteúdo visível).
- JavaScript sem exceções nos percursos testados.
- Importação inicial repetida sem duplicação de unidades.
- Atualização visual cria uma página independente com modelo vitrine; o conteúdo da página anterior é comparado antes e depois e permanece igual.
- Nova página editável no Gutenberg, sem blocos inválidos em qualquer nível, inclusive os padrões atualizados.
- ZIP instalável com pasta correta e integridade verificada.

Comandos: `node dev/smoke.cjs`, `node dev/editor-check.cjs`, `node dev/upgrade-check.cjs` e `node dev/interaction-check.cjs`. O teste de atualização só atua no WordPress local demonstrativo e publica a página exclusivamente nessa instância.

Não executado: envio real pelo WhatsApp, confirmação de consulta, conferência dos pinos no Google Maps pelo responsável, atualização na Hostinger do usuário, ativação de métricas/publicidade, publicação externa do site ou restauração em uma nova tarefa de nuvem.

As fotografias são referências de banco de imagem; créditos e licenças em CREDITOS.md no tema. Não representam clientes, funcionários ou produtos do estoque. O número fictício do teste de codificação existe apenas no DOM, sem persistência nos cadastros.

Capturas finais: `dist/novo-banner.png`, `dist/novo-banner-mobile.png`, `dist/novo-visual-desktop.png`, `dist/novo-visual-mobile.png`. As capturas de página inteira usam movimento reduzido para que seções fora da tela apareçam no registro estático; o teste de movimento verifica separadamente o modo animado.

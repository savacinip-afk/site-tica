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


## Extensão 2.1 — relógios, marcas, influencers e equipe

Validação real adicional com `node dev/expansion-check.cjs`:

- Novos rascunhos da home e do Sobre nós, com blocos Gutenberg válidos e conteúdo das duas páginas de origem preservado byte a byte.
- Repetir a instalação abre as mesmas páginas sem duplicar cadastros.
- 15 espaços de marcas, 4 de influencers, 6 de funcionários e 3 de relógios.
- Carrossel avança automaticamente, pausa com hover, completa um ciclo de 15 posições e responde às setas do teclado.
- 5 posições visíveis no desktop e 3 no celular, com os itens das duas extremidades exatamente pela metade, medidos no navegador.
- Movimento reduzido desativa o automático mantendo a navegação manual.
- Quadro da equipe e recrutamento presentes somente no Sobre nós; a home recebe apenas sua prévia institucional.
- WhatsApp e e-mail de recrutamento desativados enquanto não configurados.
- Links corretos após configurar contatos de teste, acentos codificados, rejeição de valores inválidos preservando os anteriores e restauração dos contatos originais em finally. Não houve envio de currículo, mensagem ou e-mail.
- Regressão do agendamento original e das interações, menu e responsividade da versão aprovada.

O layout 2.0 foi mantido. Cadastros reais, fotos, logos, perfis, funções e contatos de recrutamento permanecem pendentes. Os números e o e-mail usados em testes existiram apenas temporariamente no banco da demonstração local e foram removidos antes das capturas e da entrega.

Prévias novas: `dist/v21-inicio.png`, `dist/v21-marcas.png`, `dist/v21-relogios.png`, `dist/v21-influencers.png`, `dist/v21-sobre.png`, `dist/v21-equipe.png`, `dist/v21-curriculos.png`, `dist/v21-mobile.png`.


## Finalização 2.2

- Confirmado por inspeção de HTML e navegador: um único banner hero e um único H1; a repetição apontada estava no PNG longo de avaliação.
- Captura em faixas testada no desktop e no celular, mostrando conteúdo final e rodapé sem reiniciar a página. Prévia 2.1 da home também corrigida.
- Três registros iniciais de convênios; três cartões 2:1 no desktop e uma coluna no celular, sem transbordamento horizontal.
- Seção incluída uma única vez, com blocos Gutenberg válidos.
- Página final criada em rascunho; repetição da ação não duplica a página. Conteúdo anterior preservado byte a byte.
- Marcas, influencers e demais elementos anteriores mantidos; equipe e currículos permanecem fora da home.
- `node dev/final-check.cjs` passou no WordPress real de demonstração. A publicação desse teste é exclusivamente local.

Arquivos finais: `dist/v22-inicio.png`, `dist/v22-convenios.png`, `dist/v22-mobile.png` e `dist/otica-rede-v2.2.zip`.

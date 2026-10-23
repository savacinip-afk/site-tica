# Versão 2.1 — relógios, marcas e pessoas

Mantém o visual vermelho, branco e preto da versão aprovada. Adiciona novas seções sem substituir os conteúdos anteriores.

## Atualizar o WordPress já instalado

1. Baixe `otica-rede-v2.1.zip` sem descompactar.
2. WordPress → **Aparência → Temas → Adicionar novo → Enviar tema**.
3. Envie o ZIP e escolha **Substituir o atual pelo enviado**. A pasta do tema continua sendo `otica-rede`; versão 2.1.0. Faça backup antes de atualizar um site em uso.
4. Entre em **Aparência → Preparar site** e clique em **Adicionar relógios, marcas e equipe**.
5. O aviso oferece **Abrir nova página inicial** e **Abrir Sobre nós com equipe**. Ambas são criadas em rascunho. Visualize e revise antes de publicar.
6. Use o novo menu **Conteúdos da rede** para preencher materiais e contatos reais.
7. Quando decidir publicar, publique a nova home e escolha-a em **Configurações → Leitura → Página inicial**. Publique também a nova página Sobre nós; os links padrão do tema passarão a apontar para ela. As páginas anteriores ficam preservadas, e poderão ser arquivadas depois da sua revisão. Se você personalizou menus ou partes de modelo no Editor do site, confira também esses links.

O botão é repetível: abre os mesmos rascunhos sem duplicar nem substituir suas edições. A página inicial e o Sobre nós anteriores não são alterados. Se a home existente usa o layout aprovado 2.0, seu conteúdo é copiado e as novas seções são inseridas. Se só existir a versão 1, a nova home é criada com os padrões aprovados 2.0 mais os acréscimos 2.1; a página antiga permanece intacta.

Não há publicação automática nem troca automática da página inicial.

## O que aparece em cada página

**Página inicial:** categorias de óculos existentes; relógios; carrossel de marcas; seção editorial existente; lojas; benefícios; influencers; agendamento; prévia institucional no final; chamada comercial existente.

**Sobre nós:** conteúdo institucional anterior; quadro da equipe; bloco Venha fazer parte do nosso time com WhatsApp e e-mail.

A equipe e o recebimento de currículos não são adicionados à página inicial.

## Cadastros sem programação

Em **Conteúdos da rede**:

| Submenu | Conteúdo inicial | Como editar |
|---|---|---|
| Relógios | 3 espaços | Título, fotografia em Imagem destacada, texto em Resumo. Botão consulta uma unidade. |
| Marcas parceiras | 15 espaços | Nome da marca no título e logotipo em Imagem destacada. PNG/WebP com transparência costuma funcionar bem. SVG não é aceito pelo WordPress padrão. |
| Influencers | 4 espaços | Nome, fotografia, apresentação em Resumo e link real na caixa Perfil no Instagram. |
| Equipe | 6 espaços iniciais | Nome do funcionário, fotografia e cargo/função em Resumo. Adicione ou remova quantos precisar. |
| Trabalhe conosco | Contatos vazios | WhatsApp do recrutamento (55 + DDD + número) e/ou e-mail real de recrutamento. |

A ordem dos itens é definida pelo campo **Ordem**, em Atributos; números menores aparecem primeiro. Para visitantes, só aparecem cadastros publicados. Rascunhos podem ser vistos pelos editores autenticados nas prévias. Quando não há cadastros publicados, a página mantém espaços de referência explicitamente identificados. Não são apresentados nomes, logos, funcionários, perfis ou contatos reais fictícios.

Você pode adicionar ou remover itens pelos menus do WordPress. Os 15/4/6/3 espaços são a estrutura inicial, não limites rígidos. O instalador não acrescenta novos placeholders se você já cadastrou registros daquele tipo, inclusive quando os anteriores foram colocados na lixeira.

As cores, títulos, descrições e chamadas ao redor dos componentes são blocos Gutenberg. Para reposicionar uma seção, mova seu grupo na página. Para reinserir uma seção, use **Inserir → Padrões → Rede de óticas**. As listas dinâmicas são editadas nos cadastros correspondentes; suas regras de comportamento ficam no código do tema.

## Carrossel de marcas

- 15 espaços iniciais, sem logotipos inventados.
- No computador são 5 posições visíveis: 3 logos inteiros e meio logo em cada lateral.
- No celular são 3 posições para manter legibilidade: um inteiro e dois meios nas pontas.
- Avanço automático a cada 3,4 segundos, em ciclo; os itens seguintes entram pela direita.
- Pausa ao passar o mouse, ao focar com teclado, quando a seção sai da tela ou quando a aba fica oculta.
- Botão de pausa/retomada, setas, teclado e gesto horizontal no celular.
- A preferência de movimento reduzido desativa o automático; os controles manuais continuam funcionando.
- O ciclo usa cópias visuais dos itens para evitar saltos. Essas cópias não representam marcas adicionais, ficam fora da navegação e são ignoradas pelos leitores de tela.

## Influencers, equipe e currículos

Os cards de influencers usam uma estética social, com imagem, nome e acesso ao perfil. Não há seguidores, curtidas, nomes de usuários ou publicações inventados. Links de Instagram inválidos são recusados, preservando o valor anterior. Sem link cadastrado, o card indica a pendência e não abre uma conta fictícia.

O quadro de funcionários permite trocar todas as fotos, nomes e funções. Os espaços iniciais usam ilustrações de pessoa, não fotografias de indivíduos apresentados falsamente como funcionários.

WhatsApp e e-mail de recrutamento são independentes dos contatos de agendamento das lojas. Ambos ficam indisponíveis enquanto não houver dados válidos. O WhatsApp abre uma conversa com mensagem pronta; o e-mail abre o aplicativo do visitante com assunto e texto preenchidos. **O candidato precisa anexar seu currículo no próprio WhatsApp ou e-mail antes de enviar.** O link não pode anexar arquivos automaticamente e não confirma vaga ou contratação. O tema não recebe, transmite ou armazena currículos no WordPress, nem exige servidor SMTP para esse fluxo.

Revise a Política de Privacidade para informar a finalidade, o responsável e a retenção dos currículos antes de ativar o recrutamento.

## Pendências de conteúdo

Logos das marcas e confirmação das parcerias; fotos e informações dos relógios; fotos, nomes e perfis dos 4 influencers; fotos, nomes e cargos da equipe; WhatsApp e/ou e-mail de recrutamento. Nenhum número ou e-mail foi inventado na configuração entregue.

Os arquivos e ilustrações são locais e o funcionamento básico não depende de serviço pago.

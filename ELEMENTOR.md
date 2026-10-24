# Edição com Elementor gratuito — tema 3.0

**Não apague o site nem as páginas atuais.** Esta atualização cria cópias independentes em rascunho, preserva o conteúdo original e reutiliza os cadastros existentes.

## Instalação na Hostinger

1. Faça backup se o site já estiver em uso. Baixe `otica-rede-v3-elementor.zip`, sem descompactar.
2. No WordPress: **Aparência → Temas → Adicionar novo → Enviar tema**. Envie o ZIP e escolha **Substituir o atual pelo enviado**. A pasta do tema continua sendo `otica-rede`.
3. Vá em **Plugins → Adicionar plugin**. Procure **Elementor Website Builder**, do autor **Elementor.com**, instale a versão gratuita compatível com seu WordPress e ative.
4. Se aparecerem ofertas de Pro, IA, modelos pagos ou conexão de conta, você pode ignorar. Este projeto não exige Elementor Pro nem conta paga.
5. Abra **Aparência → Preparar Elementor**.
6. No campo da página inicial, escolha **Início — versão final com convênios** (ou o nome atual da página aprovada que você já editou).
7. Clique em **Preparar páginas de teste para Elementor**.
8. Use o link **Editar … com Elementor** na confirmação. Aguarde a tela de carregamento do Elementor terminar.

O preparo cria cópias de Início, Sobre nós, Produtos, Nossas lojas, Agendamento, Blog e Política de Privacidade, quando essas páginas existirem. As cópias recebem o sufixo **— Elementor**. Na lista de Páginas, pesquise **Elementor** para encontrá-las facilmente. Textos, imagens e links são extraídos das páginas existentes no seu WordPress; o nome da empresa, os contatos e os cadastros não são redefinidos.

Clicar novamente abre as mesmas cópias sem sobrescrever suas edições no Elementor. A página inicial ativa não muda. Se preferir continuar com o Gutenberg, suas páginas anteriores permanecem disponíveis.

## Editar o conteúdo

- **Texto ou título:** clique no texto da página; use o controle que abre no painel do Elementor.
- **Foto principal:** selecione **Trocar foto principal** na Estrutura/Navegador, ou o widget Imagem correspondente, e escolha outra imagem no painel.
- **Botão:** selecione o botão e altere Texto e Link.
- **Ordem das seções:** abra **Estrutura/Navegador** (ícone de camadas). Os grupos têm nomes como Banner principal, Produtos, Relógios, Marcas parceiras, Convênios e Influencers. Arraste o contêiner completo para mover a seção com todos os seus elementos.
- **Celular:** use os controles responsivos do Elementor e confira também a prévia real.
- **Salvar sem publicar:** no menu junto de **Publicar**, escolha **Salvar rascunho**. A posição desse menu varia entre versões do Elementor.
- **Testar formulário e efeitos:** use **Visualizar**. Durante a edição, alguns movimentos ficam pausados para facilitar a seleção dos elementos.

A página não está presa em um único bloco HTML: usa contêineres, títulos, textos, imagens e botões nativos do Elementor.

## O que continua nos cadastros

Os componentes dinâmicos usam o widget **Cadastros da rede**, na categoria **Rede de Óticas** do Elementor. Você pode mover o widget ou seu contêiner, mas seus dados continuam centralizados:

| Conteúdo | Onde alterar |
|---|---|
| Lojas, endereços e WhatsApps | Unidades |
| Produtos e categorias | Produtos e categorias |
| Relógios, marcas, convênios e influencers | Conteúdos da rede |
| Funcionários e cargos | Conteúdos da rede → Equipe |
| WhatsApp/e-mail para currículos | Conteúdos da rede → Trabalhe conosco |
| Artigos do blog | Posts |

O painel do widget inclui atalhos para esses cadastros. Assim você não precisa alterar o mesmo endereço, telefone ou logotipo em várias páginas. O blog utiliza uma consulta de posts do tema, sem depender do widget de posts do Elementor Pro.

**Cabeçalho e rodapé permanecem compartilhados pelo tema**, editáveis em **Aparência → Editor**. O nome comercial fica em **Configurações → Geral** e o logotipo no bloco Logotipo do site. A edição global dessas duas partes não foi transferida ao construtor de temas do Elementor Pro.

## Revisar e colocar no ar depois

As cópias ficam em rascunho e os links entre elas funcionam na prévia para o administrador autenticado. O agendamento mantém a seleção da unidade, inclusive ao sair do cartão para a página de agendamento.

Quando revisar e aprovar tudo, publique as novas páginas que deseja usar e selecione a nova inicial em **Configurações → Leitura**. Os links padrão passam a usar as páginas Elementor publicadas. Até lá, o site atual continua como estava. Confira menus personalizados e URLs antes da troca final.

Evite editar a mesma cópia alternando entre Gutenberg e Elementor. As páginas originais já são o seu caminho de retorno. Depois da troca, não desative o Elementor enquanto estiver usando as páginas construídas com ele.

## Notas técnicas e limites

- A integração é incluída no tema e usa as APIs e widgets gratuitos do Elementor. O plugin Elementor é instalado separadamente pelo WordPress, sem redistribuir ou modificar seu código.
- O conversor cobre os blocos usados neste projeto. Conteúdos adicionais criados com outros plugins podem precisar de revisão; a página original é preservada.
- Há um modelo PHP compatível com o tema de blocos, que prepara módulos de navegação e recursos antes de imprimir o cabeçalho HTML.
- As fontes Manrope e Barlow Condensed do layout continuam locais. Recursos opcionais de nuvem ou fontes adicionais do Elementor não são necessários para os componentes entregues.
- A estrutura visual e os espaçamentos de referência seguem o CSS do tema, para manter o desenho aprovado. Alterações avançadas que conflitem com esses estilos podem exigir manutenção técnica.
- A lógica dos formulários e dos carrosséis continua no tema. Para alterar textos ao redor deles, use o Elementor; para alterar perguntas ou regras do formulário, é necessária manutenção técnica.
- A migração não publica, não remove páginas, não escolhe automaticamente uma página inicial e não substitui informações comerciais por exemplos.

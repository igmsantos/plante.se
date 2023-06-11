**PLANTE.SE**

## Missão:

Trazer empresas e profissionais envolvidos com agricultura urbana,
jardinagem e paisagismo para o mundo digital, permitindo que ofereçam
seus produtos e serviços através de uma plataforma limpa e objetiva.

As empresas e profissionais se cadastram através do painel
administrativo onde é possível customizar a vitrine com o nome, logo,
imagens e descrição, e podem criar artigos para trazer credibilidade e
atrair os clientes.

Os clientes podem ler os artigos e saber mais sobre o autor e empresa
envolvida, podendo enviar orçamentos para um ou mais profissionais e
negociar utilizando a plataforma.

A plataforma oferece o Mall(shopping) onde o cliente consegue localizar
empresas, profissionais, produtos e serviços por geolocalização,
localidade e buscas.
  

## Estrutura do site:

-   Admin

    -   CRUD de usuarios do site (pessoas que leem os artigos, compram
        > ou contratam coisas, e para isso fazem orçamentos)

        -   Edição de infos pessoais

        -   Gerenciamento de orçamentos (orçamentos enviados e respostas
            > recebidas)

        -   Favoritos (itens favoritados do site)

    -   Gerenciamento da Plataforma/Conteúdo

        -   Listagem e CRUD de vitrines e galerias

        -   Listagem e CRUD de artigos

        -   Listagem e CRUD de produtos/serviços

        -   Listagem e CRUD de orçamentos

    -   CRUDS de profissionais e empresas

        -   Edição de informações, edição de vitrine, galeria de fotos e
            > campo de descrição, possibilidade de anexar documentos

        -   CRUD de artigos criados

        -   CRUD de produtos/serviços oferecidos

        -   Gerenciamento de produtos e serviços vendidos

        -   Gerenciamento de orçamentos recebidos com possibilidade de
            > respostas, dialogo

-   Website

-   Home

    -   Lista de artigos

        -   Detalhes do artigo

            -   Favoritar

        -   Detalhes da empresa

            -   Favoritar

    -   Area promocional

        -   Detalhes da empresa

            -   Favoritar

    -   Serviços em destaque

        -   Detalhes do serviço

            -   Faça um orçamento

            -   Detalhes da empresa/profissional

            -   Favoritar

    -   Produtos em destaque

        -   Detalhes do produto

        -   Adicionar ao carrinho

            -   Adicionar favoritos

            -   Detalhes da empresa

    -   Busca ( pode ser lateral ou campo superior )

        -   Campo de busca

        -   Busca por localidade

        -   Busca por tipo de serviço

        -   Busca por categoria de produto

        -   Lista de resultados

            -   Detalhes do serviço, produto ou artigo

        -   Cadastro de usuário

        -   Cadastro de profissional/empresa

        -   Dúvidas frequentes

        -   Entre em contato

        -   Quem somos?


## Requisitos de funcionalidade:

**Login através de redes sociais:** Possibilitar criação de contas
através do google account.

O usuário precisa estar cadastrado para ver o telefone e enviar
orçamentos.

**Múltiplos users por empresa/profissional:** Após a empresa cadastrada
(email principal/admin) é possível cadastrar contas de acesso
secundárias vinculadas a empresa com permissões específicas para os
funcionários.

**Recomendações por geolocalização:** As recomendações e ordenação de
produtos e serviços ocorrem de acordo com a proximidade entre o usuário
e o fornecedor. A localização é adquirida por meio do browser via JS e
como fallback via GeoIP.

**SEO baseado em links de busca e tags:** Gerar permalinks através de
slugs para todas as possibilidades de buscas para que os crawlers de
busca reforcem a exposição nos buscadores.

**Categorias**:

1.  Agricultura Urbana

    -   Plantas frutíferas

        -   Clima seco

        -   Clima quente

        -   Plantas de solo

    -   Hortaliças

    -   Ervas e temperos

    -   Plantas medicinais

    -   Cultivo em pequenos espaços (varandas, pátios, etc.)

    -   Compostagem urbana

2.  Jardinagem

    -   Jardinagem orgânica

    -   Jardinagem de interior

    -   Jardins de rochas e suculentas

    -   Jardins de água e lagoas

    -   Jardins de borboletas / atrativos para a vida selvagem

    -   Plantas ornamentais

    -   Ferramentas e equipamentos de jardinagem

3.  Paisagismo

    -   Paisagismo residencial

    -   Paisagismo comercial

    -   Paisagismo de baixa manutenção

    -   Paisagismo sustentável / ecológico

    -   Design de hardscape (pátios, muros, caminhos, etc.)

    -   Iluminação de paisagem

    -   Irrigação e drenagem

4.  Educação e Treinamento

    -   Tutoriais de jardinagem e paisagismo

    -   Cursos e workshops online

    -   Livros e recursos educacionais

5.  Serviços Profissionais

    -   Consultoria de jardinagem e paisagismo

    -   Serviços de manutenção de jardins

    -   Serviços de design e instalação de paisagens

6.  Loja

    -   Sementes e mudas

    -   Ferramentas e equipamentos

    -   Materiais de jardinagem e paisagismo (solo, adubo, pedras, etc.)

    -   Decoração de jardim (estatuetas, vasos, móveis, etc.)

    -   Imóveis

    -   Máquinas

    -   Beneficiamentos

**Monetização:**

1.  **Taxas de Associação:** Cobrar uma taxa de associação das empresas
    > ou profissionais que desejam se registrar em seu site. Isso pode
    > ser uma taxa única, uma assinatura mensal ou anual.

2.  **Comissões:** Ganhar dinheiro cobrando uma comissão ou uma taxa
    > sobre cada transação que ocorrer através de seu site. Por exemplo,
    > se um cliente contrata um profissional através de seu portal, você
    > pode cobrar uma porcentagem do valor do contrato.

3.  **Publicidade:** Ganhar dinheiro vendendo espaço publicitário em seu
    > site. Isso pode ser na forma de banners, anúncios em vídeo, posts
    > patrocinados ou anúncios de texto.

4.  **Parcerias e Patrocínios:** Parcerias com empresas relacionadas e
    > obter patrocínio para certos aspectos do site ou para eventos que
    > você organiza.

5.  **Venda de Produtos ou Serviços:** Vender produtos ou serviços
    > diretamente em seu site. Isso pode ser qualquer coisa, desde
    > produtos de jardinagem até cursos online ou livros.

6.  **Freemium:** Oferecer alguns recursos do seu site gratuitamente,
    > mas cobrar uma taxa para acesso a recursos premium. Por exemplo,
    > todos os usuários podem ter acesso a artigos e listas básicas, mas
    > talvez eles precisem pagar para ter acesso a listas detalhadas,
    > conselhos de especialistas, etc.

7.  **Leads qualificados:** Para empresas que estão procurando por
    > clientes específicos, você pode cobrar uma taxa por leads
    > qualificados. Por exemplo, se uma empresa de paisagismo está
    > procurando por clientes em uma determinada cidade, você pode
    > cobrar uma taxa por cada lead que você fornecer a eles nessa
    > cidade.

8.  **Mercado de Projetos:** Nesse modelo, os usuários (sejam eles
    > profissionais ou amadores) poderiam postar projetos de paisagismo,
    > jardinagem ou agricultura urbana que eles criaram. Isso poderia
    > incluir desenhos, planos de plantio, listas de materiais
    > necessários, etc. Outros usuários, então, poderiam comprar esses
    > projetos para implementá-los em suas próprias casas ou negócios.

9.  **Plantio de Árvores Virtual:** Neste modelo, os usuários poderiam
    > \"comprar\" árvores virtuais em seu site. Para cada árvore virtual
    > comprada, uma árvore real seria plantada em uma área de
    > reflorestamento ou em um ambiente urbano que precisa de mais
    > vegetação. As árvores virtuais poderiam ser exibidas em um perfil
    > de usuário, permitindo que os usuários mostrem o quanto eles
    > contribuíram para o plantio de árvores.

**Resumo de negócio:**

**1. Resumo Executivo:**

O portal Plante.se visa conectar empresas e profissionais envolvidos com
agricultura urbana, jardinagem e paisagismo com clientes através de uma
plataforma online intuitiva e fácil de usar. As empresas e profissionais
podem listar seus produtos e serviços, enquanto os clientes podem
explorar, aprender e fazer orçamentos. A plataforma também promoverá a
sustentabilidade através de programas inovadores como o Plantio de
Árvores Virtual.

**2. Descrição da Empresa:**

Plante.se, um portal baseado na web que atende a profissionais e
empresas do setor de agricultura urbana, jardinagem e paisagismo, assim
como a clientes procurando tais serviços e produtos.

**3. Serviços:**

Plante.se oferece um portal onde profissionais e empresas podem listar e
vender seus produtos e serviços. Os clientes podem procurar
profissionais e empresas por localidade, ler artigos relacionados,
solicitar orçamentos e participar de iniciativas ecológicas, como o
Plantio de Árvores Virtual.

**4. Análise de Mercado:**

O público-alvo do Plante.se são empresas e profissionais do setor de
agricultura urbana, jardinagem e paisagismo, assim como indivíduos e
empresas procurando tais serviços. O mercado está crescendo, pois mais
pessoas estão interessadas em ter ambientes verdes em suas casas e
escritórios.

**5. Estratégia de Marketing:**

Plante.se planeja se promover através de SEO, redes sociais, parcerias
estratégicas e patrocínios, além de iniciativas ecológicas para atrair
usuários conscientes do meio ambiente.

**6. Estrutura Operacional:**

O portal será desenvolvido usando NodeJS e Express.js no backend, React
no frontend e MongoDB como banco de dados. Keycloak será usado para
autenticação e gerenciamento de acesso, enquanto o Google Analytics ou
Firebase Analytics serão usados para acompanhar e analisar o desempenho
do site.

**7. Estratégia de Monetização:**

A receita será gerada através de várias fontes, incluindo taxas de
associação, comissões sobre transações, publicidade, venda de projetos e
venda de árvores virtuais.

**8. Previsão Financeira:**

Detalhes sobre os custos operacionais, expectativas de receita, ponto de
equilíbrio e projeções financeiras serão preenchidos com base em uma
análise mais detalhada do mercado e dos custos de implementação.

**9. Resumo:**

O portal Plante.se visa preencher uma lacuna no mercado, permitindo que
profissionais e empresas do setor de agricultura urbana, jardinagem e
paisagismo se conectem com clientes de maneira fácil e eficiente, ao
mesmo tempo em que promovem práticas sustentáveis e conscientização
ambiental. A plataforma será desenvolvida usando tecnologias modernas e
escaláveis para garantir uma experiência de usuário suave e segura.

**Cronograma**

1.  **Planejamento (1 semana):** Defina os requisitos, esboce as
    > funcionalidades, identifique as dependências e prepare um roadmap
    > para o desenvolvimento.

2.  **Configuração do ambiente de desenvolvimento (1 semana):**
    > Configurar o ambiente de desenvolvimento incluindo Node.js,
    > Express.js, React, MongoDB e Docker.

3.  **Desenvolvimento do Backend (8-10 semanas):** Comece com a
    > modelagem do banco de dados e continue com a criação de APIs
    > RESTful para cada funcionalidade.\
    > a. Configuração de Banco de dados e Modelos (2 semanas)\
    > b. Autenticação e Autorização (2 semanas)\
    > c. APIs para CRUD de usuários, profissionais e empresas (2
    > semanas)\
    > d. APIs para CRUD de artigos, produtos e serviços (2 semanas)\
    > e. API para gerenciamento de orçamentos e favoritos (1-2 semana)

4.  **Desenvolvimento do Frontend (8-10 semanas):** Comece com o esboço
    > da interface do usuário e prossiga com a implementação das
    > visualizações e componentes.\
    > a. Configuração do ambiente de desenvolvimento React (1 semana)\
    > b. Criação da interface de usuário básica (3 semanas)\
    > c. Implementação de autenticação e autorização (1 semana)\
    > d. Implementação das funcionalidades do usuário (2 semanas)\
    > e. Implementação das funcionalidades de profissionais e empresas
    > (2 semanas)\
    > f. Revisão e ajustes finais (1 semana)

5.  **Testes (4 semanas):** Execute testes unitários, de integração e de
    > aceitação do usuário para garantir que o portal esteja funcionando
    > conforme esperado.

6.  **Lançamento e Monitoramento (1 semana):** Prepare-se para o
    > lançamento, faça o deploy do portal e monitore o desempenho, a
    > usabilidade e possíveis bugs.

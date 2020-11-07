<template>
  <div class="home">
    <div class="container">
      <h1><strong>Wordpress e JAMStack:</strong><br>vocês podem ser bons amigos</h1>
      <h2>Introdução</h2>
      <p>Esta palestra vai tratar sobre as possibilidade de trabalho utilizando o Wordpress, um estável e seguro ambiente de desenvolvimento, com as JAMstacks, que são ótimas ferramentas modernas de desenvolvimento de sites estáticos. Vamos aparar as arestas e oferecer possibilidades de trabalho em conjunto com ambas as ferramentas.</p>
      <figure>
        <picture>
          <source srcset="~assets/img/amigos.avif" type="image/avif">
          <source srcset="~assets/img/amigos.webp" type="image/webp">
          <source srcset="~assets/img/amigos.jpg" type="image/jpg">
          <img src="~assets/img/amigos.jpg" alt="Meninos pequenos andando um na frente do outro." width="865" height="500">
        </picture>
        <figcaption>Amigos! &lt;3</figcaption>
      </figure>
      <h2>Senta que lá vem história</h2>
      <p>Se você está a mais de 10 anos no mercado, deve ter ouvido falar ou mesmo ter trabalhado com algumas das tecnologias que vou citar abaixo:</p>
      <ul>
        <li>jQuery</li>
        <li>Wordpress</li>
        <li>Angular</li>
        <li>React & Redux</li>
        <li>Vue & Vuex</li>
        <li>Svelte</li>
        <li>Typescript</li>
      </ul>
      <p>A lista tende a ser muito grande, citei alguns aqui de cabeça. Em resumo, o desenvolvimento web passa pelas linguagens de front-end e de back-end, que temos no mercado. Vou comentar da minha experiência como desenvolvedor front-end, nas linguagens <strong>php</strong> e <strong>javascript</strong>. Sempre trabalhei desenvolvendo temas em Wordpress, pois meu público-alvo eram agências que terceizavam projetos.</p>
      <p>O Wordpress se estabeleceu no mercado mundial tendo hoje <strong>35%</strong> dos websites no mundo, crescendo <strong>2%</strong> se comparando com 2019 e <strong>4%</strong> se comparando com o ano anterior (fonte <a href="https://hostingtribunal.com/blog/wordpress-statistics/" target="_blank" rel="noopener noreferrer">https://hostingtribunal.com/blog/wordpress-statistics/</a>). Não dá pra negar que é o <strong>o nome de CMS mais lembrado</strong> nas cabeças dos desenvolvedores, gestores e publicitários. A documentação extensa, com a facilidade de criar temas (ou instalar temas prontos) faz com que seja uma opção barata e confiável para clientes, pois basta um servidor compartilhado com ao menos 256Mb de RAM para rodar.</p>
      <p>Por outro lado, o desenvolvimento de soluções em javascript está evoluindo numa velocidade altíssima, com lançamentos anuais de atualizações da linguagem, favorecido pelos 4 cavaleiros do apocalípse <strong>React, Vue, Angular e Svelte</strong>. Desenvolvedores gostam de brinquedos novos, seguem <i>hypes</i> e gostam da experiência de desenvolvimento em uma única stack.</p>
      <p>Nisto apresentamos, para o interlocutor que ainda está curioso, o termo <a href="https://jamstack.org/" target="_blank" rel="noopener noreferrer">JAMstack</a>. Segundo William Oliveira, no seu blog:</p>
      <figure>
        <blockquote>
          JAM é como LAMP (Linux, Apache, MySQL e PHP), um acrônimo para JavaScript, APIs e Markup. Onde temos uma marcação (HTML), que é gerada durante o deploy com um gerador de site estático, como o Hexo ou o Jekyll, que usei para criar este blog; caso seja um PWA o app será gerado durante o deploy e todo o restante é com o JavaScript e as APIs. Qualquer alteração de conteúdo, ação na interface ou algo do tipo, deve ser feito com JavaScript e os dados devem vir através de uma API. É o que já fazemos em Single Page Applications, mas agora também pensando em websites. Assim como nas SPAs, não devemos consultar o banco de dados, renderizar o HTML e enviar para o cliente via backend (com um PHP, Python ou a ferramenta que for), pois todo o conteúdo já foi renderizado e enviado para o usuário final.
        </blockquote>
        <figcaption>Fonte: <a href="https://woliveiras.com.br/posts/jamstack-introdu%C3%A7%C3%A3o-o-que-%C3%A9-jamstack/" target="_blank" rel="noopener noreferrer">https://woliveiras.com.br/posts/jamstack-introdu%C3%A7%C3%A3o-o-que-%C3%A9-jamstack/</a> </figcaption>
      </figure>
      <p>As principais JAMstacks do mercado são <a href="https://www.gatsbyjs.com/" target="_blank" rel="noopener noreferrer">Gatsby</a>, <a href="https://nextjs.org/" target="_blank" rel="noopener noreferrer">Next.js</a>, <a href="https://nuxtjs.org/" target="_blank" rel="noopener noreferrer">NUXT</a>, <a href="https://gohugo.io/" target="_blank" rel="noopener noreferrer">Hugo</a>, <a href="https://jekyllrb.com/" target="_blank" rel="noopener noreferrer">Jekyll</a>, <a href="https://gridsome.org/" target="_blank" rel="noopener noreferrer">Gridsome</a>, <a href="https://jamstack.org/generators/" target="_blank" rel="noopener noreferrer">entre outras</a>.</p>
      <h2>O sangue está esquentando</h2>
      <p>Para ajudar ainda mais neste caldo de contradições, soluções em Javascript e Node como <strong>Netlify</strong>, <strong>Strapi</strong>, entre outras tem crescido entre os desenvolvedores que gostam de trabalhar com uma única linguagem. </p>
      <p>Enquanto isto, o Wordpress mantem decisões duvidosas como manter o suporte para versões antigas dos Browsers utilizando oficialmente uma versão insegura de jQuery, a 1.12.4, <a href="https://snyk.io/test/npm/jquery/1.12.4" target="_blank" rel="noopener noreferrer">apontado aqui</a>.</p>
      <p>Por outro lado, é inegável que o WP se mantem dominante mercado, definindo um padrão na cabeça de gestores e clientes. A usabilidade dele foi testada por milhões de usuários, que não querem pagar mensalidade de uso ou alguma licença por ele, sem perder o poder de configuração. Muitos plugins de SEO, cache e gestor de conteúdo rico ajuda ele a ser amigável para não desenvolvedores. E mesmo soluções como o Woocommerce, que é uma forma barata de ter uma loja online em um ambiente único.</p>
      <h2>Treta!!</h2>
      <figure>
        <picture>
          <source srcset="~assets/img/inimigos.avif" type="image/avif">
          <source srcset="~assets/img/inimigos.webp" type="image/webp">
          <source srcset="~assets/img/inimigos.jpg" type="image/jpg">
          <img src="~assets/img/inimigos.jpg" alt="Meninos pequenos andando um na frente do outro." width="865" height="500">
        </picture>
        <figcaption>Inimigos! &lt;/3</figcaption>
      </figure>
      <p>Como é natural de um ambiente muito competitivo, os principais players mantiveram suas opiniões guardadas dentro de seus círculos, evitando tretas em escala interplanetária. Mas o sangue esquentou! Como bons acompanhadores de treta, temos o dever histórico de destrinchar o certame para nossos amigos.</p>
      <figure>
        <blockquote cite="https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/">
          “O JAMstack é uma regressão para a grande maioria das pessoas que o adotam. ” (...) “A usabilidade e funcionalidade é até inferior. Até mesmo a reconstrução de sites no JAMstack remonta aos dias do Movable Type, onde quanto maior o seu site fica, mais lento é para reconstruir ou atualizar os modelos.”
        </blockquote>
        <figcaption>Matt Mullenweg, criador do WP. Fonte: <a href="https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/" target="_blank" rel="noopener noreferrer">https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/</a> (traduzido pelo Google Tradutor)</figcaption>
      </figure>

      <p>Em poucas palavras, Matt Mullenweg acredita que a JAMstack é um retrocesso em termos de usabilidade e funcionalidade, comparando-a com o Movable Type. Continuando:</p>
      <figure>
        <blockquote cite="https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/">
          “Você pode consertar uma dúzia de serviços, cada um com sua própria conta e faturamento, por centenas de dólares por mês, para obter um resultado semelhante que você teria por alguns dólares por mês usando WordPress em hospedagem compartilhada ”, disse ele. “E seria mais frágil, porque a corrente é tão forte quanto seu elo mais fraco. Você está encadeando diferentes conjuntos de ferramentas, logins, faturamento, hospedagem ... qualquer parte disso pode quebrar todo o fluxo.”
        </blockquote>
        <figcaption>Matt Mullenweg. Fonte: <a href="https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/" target="_blank" rel="noopener noreferrer">https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/</a> (traduzido pelo Google Tradutor)</figcaption>
      </figure>
      <p>Aqui ele traz algo que é o grande fiel da balança para o Wordpress: um projeto em Wordpress pode ser bem barato para ser mantido online, em comparação à outros projetos que tendem a ter como modelo de negócio a limitação de postagens e de formulários (sim, ele apontou o dedo para o Netlify). Basta uma hospedagem compartilhada, daquelas que encontramos aos montes no Brasil.</p>
      <p>Mas como gostamos de expor as contradições, vamos pegar as melhores falas:</p> 
      <figure>
        <blockquote>
          “Muitas vezes há um momento certo quando uma tecnologia antiga está prestes a ser substituída pela próxima, onde o principal líder no campo sai e faz um forte argumento de que absolutamente nada está acontecendo (...) Um momento que acaba parecendo uma virada onde o novo estava inegavelmente presente o suficiente para valer a pena ser negado.”
        </blockquote>
        <figcaption>Mathias Biilmann, CEO do Netlify. Fonte: <a href="https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/" target="_blank" rel="noopener noreferrer">https://thenewstack.io/wordpress-co-founder-matt-mullenweg-is-not-a-fan-of-jamstack/</a> (traduzido pelo Google Tradutor)</figcaption>
      </figure>
      <p>A provocação que Mathias Biilman, CEO da Netlify é válida. O crescimento da adoção da JAMstack está a um nível sensível na comunidade, com muitos desenvolvedores adotando soluções de sites estáticos que estão disponíveis globalmente na nuvem a uma velocidade quase instantânea. Claro que os criadores das JAMstacks estão cientes da necessidade de builds mais rápidas, logo o ponto de Mullenweg perderá sentido num futuro próximo.</p>
      <figure>
        <blockquote>
          “O Jamstack é uma arquitetura que está conquistando as mentes dos desenvolvedores em todo o mundo e em toda a pilha de desenvolvimento da web (...) A adoção de novas arquiteturas geralmente começa com os desenvolvedores, então estou animado em ver uma empresa como, digamos, a Netlify ostentar mais de 1 milhão de desenvolvedores em sua plataforma Jamstack.”
        </blockquote>
        <figcaption>Ohad Eder-Pressman, co-founder and CEO of Stackbit (Fonte: <a href="https://wptavern.com/matt-mullenweg-and-jamstack-community-square-off-making-long-term-bets-on-the-predominant-architecture-for-the-web" target="_blank" rel="noopener noreferrer">https://wptavern.com/matt-mullenweg-and-jamstack-community-square-off-making-long-term-bets-on-the-predominant-architecture-for-the-web</a>) (Traduzido pelo Google Tradutor)</figcaption>
      </figure>
      <p>Um ponto muito importante é que desenvolvedores gostam de desafios, e de buscar soluções alternativas para os problemas. A linguagem javascript, que é o ponto chave para o desenvolvimento web, e que está em um ritmo atualizado de inovações, faz com que a adoção das JAMstacks cresça a um ritmo frenético, da mesma forma que ocorreu com o Wordpress a uns 15 anos atrás.</p>
      <h2>Chegou a turma do deixa disso</h2>
      <p>Ambas as perspectivas apresentam pontos válidos. Nosso papel nesta palestra é que eles <strong>COEXISTAM</strong> pacificamente, como um pai que vê as tretas entre os filhos e intervem pelo bem da casa. Para que as coisas voltem a normalidade, cada lado vai ter que ceder.</p>
      <div class="block">
        <div class="block-text">
          <h3>Wordpress</h3>
          <p>Você vai ser o gerenciador de conteúdo. Confiamos em você pra gerir tipos de postagens, upload de mídias, conteúdos diversos e campos personalizados com o seu nobre amigo <strong>Advanced Custom Fields</strong>. O <strong>Carbon Fields</strong> também pode brincar aqui, mas o <strong>Elementor, WP Bakery, Divi</strong> não podem te visitar. E você não vai mais gerenciar temas, só <strong>functions.php</strong> terá papel fundamental. E você não poderá ter mais os privilégios de <strong>monolito</strong>.</p>
        </div>
        <img src="~assets/img/wp.svg" alt="Wordpress" width="200" height="200">
      </div>
      <div class="block">
        <div class="block-text">
          <h3>JAMstack</h3>
          <p>Desculpe <strong>Netlify</strong>, não vamos usar você. Nada pessoal, sabe né, o cliente gosta de Wordpress. Por outro lado, você ficará responsável pelo front-end, em outra camada de desenvolvimento. Você vai ter que configurar as ferramentas do webpack (ou rollup), testes, deploy por conta.</p>
        </div>
        <img src="~assets/img/jamstack.svg" alt="JAMstack" width="200" height="100">
      </div>
      <p>Creio que seja melhor assim: cada um cede, e a gente integra todos numa grande mesa de bar. Cada um sentadinho num canto, com seu serviço em uma camada a parte - a camada do front e a camada do backend. Não <a href="https://twitter.com/sseraphini" target="_blank" rel="noopener noreferrer">Sibelius</a>, não é micro-serviços aqui. (PS: sigam ele, ele comenta bastante sobre micro-serviços).</p>
      <h2>Wordpress paga a primeira cerveja</h2>
      <p>Uma das coisas mais fantásticas do Wordpress é a sua API Rest. Em qualquer projeto wordpress, você pode acessar a API dele com a URL <strong>wp-json</strong>. Curioso? Alguns exemplos:</p>
      <ul>
        <li>https://wp.mateusavila.com.br/wp-json/</li>
        <li>https://bienaldolivro.com.br/wp-json/</li>
        <li>https://anticast.com.br/wp-json/</li>
      </ul>
      <p>A integração com o plugin Advanced Custom Fields é potencializada com o plugin <strong>ACF to REST API</strong> (<a href="https://br.wordpress.org/plugins/acf-to-rest-api/" target="_blank" rel="noopener noreferrer">https://br.wordpress.org/plugins/acf-to-rest-api/</a>), que insere os tipos personalizados nas devidas rotas automaticamente.</p>
      <p>Se você quiser expandir estas funções da API do WP, recomendo estudar a implementação da função <strong>register_rest_route</strong> (<a href="https://developer.wordpress.org/rest-api/extending-the-rest-api/adding-custom-endpoints/" target="_blank" rel="noopener noreferrer">https://developer.wordpress.org/rest-api/extending-the-rest-api/adding-custom-endpoints/</a>), que registra uma rota personalizada. Abaixo um exemplo bem simples dela em ação:</p>
<pre><code><?php
<span class="comment">// adicione o suporte para CORS</span>
function add_cors_http_header(){
  header("Access-Control-Allow-Origin: *");
}
add_action('init','add_cors_http_header');

<span class="comment">// adicione uma rota e bote dentro da init</span>
add_action('rest_api_init', function () {
  register_rest_route( '/options', '/v1', array(
    'methods' => 'GET',
    'callback' => 'get_options'
  ));
});

<span class="comment">// repare na chave callback, vamos chamar ela aqui embaixo</span>
function get_options (WP_REST_Request $request) {
  return wp_send_json(array(
    'facebook' => "pode ser qualquer código do wordpress, por exemplo um get_option('facebook')"
  ), 200);
}
<span class="comment">// na função acima, é bem simples, retorna a string apenas.</span>
<span class="comment">// Se for acessar em seu projeto, a url seria http://URL-DO-PROJETO/wp-json/options/v1</span>
</code></pre>
      <h2>A JAMstack paga a batata-frita</h2>
      <p>Sabendo das rotas certinhas, uma boa prática para otimizar a sua aplicação é usar a função <strong>Promise.All</strong> e resolver todas estas requisições numa hora só, para aumentar a performance. Abaixo um exemplo bem simples:</p>
<pre><code><span class="comment">// Considere o valor de process.env.BASE_APIWP como o valor do .env da sua aplicação. Se quiser botar a URL direta, fique a vontade.</span>
Promise.all([
  fetch(process.env.BASE_APIWP + '/wp/v2/pages/?slug=home&_fields=acf', { mode: 'cors' }),
  fetch(process.env.BASE_APIWP + '/menu/v1', { mode: 'cors' }),
  fetch(process.env.BASE_APIWP + '/options/v1', { mode: 'cors' })
]).then(async ([homeResource, menuResource, optionsResource]) => {
  const home = await homeResource.json()
  const menu = await menuResource.json()
  const options = await optionsResource.json()
  return { home, menu, options }
}).then((response) => {
  const homePage = response.home[0]
  const menu = response.menu
  const options = response.options
  <span class="comment">// aqui embaixo vocês inserem dentro do seu framework.</span>
})
</code>
</pre>
    <h2>Agora que beberam bastante cerveja e comeram batata frita</h2>
    <p>Você pode desenvolver projetos unindo estes dois mundos em duas camadas, atendendo clientes, desenvolvedores e gestores, todos felizes. Até alguma tecnologia aparecer e mudar tudo de novo.</p>
    <figure>
        <picture>
          <source srcset="~assets/img/melhores-amigos.avif" type="image/avif">
          <source srcset="~assets/img/melhores-amigos.webp" type="image/webp">
          <source srcset="~assets/img/melhores-amigos.jpg" type="image/jpg">
          <img src="~assets/img/melhores-amigos.jpg" alt="Meninos pequenos andando um na frente do outro." width="620" height="620">
        </picture>
        <figcaption>Melhores amigos! &lt;3</figcaption>
      </figure>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  layout: 'page'
})
</script>

<style lang="stylus">
  figure
    margin 30px 0
    blockquote
      background #fff
      border 1px solid #cacaca
      padding 30px
      font-style italic
      line-height 1.5
      color #404041
      margin-bottom 5px
    picture
      img
        max-width 100%
        height auto
        display block
        margin-bottom 5px
    figcaption
      font-size 14px
      color #404040
  .warning
    padding 20px
    background #d63031
    color #fff
    width 100%
    margin 30px 0
    border-radius 3px
    p 
      margin 0
      color #fff
    h3
      color #fff
  pre
    margin 20px 0
    padding 0
    background #000
    border-radius 3px
    code
      color #fff
      padding 20px
      overflow auto
      display block
    .comment
      color #999
  .home
    margin-top 120px
  .image-full
    width 100%
    display flex
    justify-content center
    margin-bottom 30px
    img
      max-width 100%
      display block
      height auto
  .block
    display flex
    justify-content space-between
    flex-wrap wrap
    align-items flex-start
    margin 30px 0
    img
      max-width 200px
    .block-text
      width calc(100% - 250px)
  h1
    font-size 30px
    text-align center
    margin 0 0 50px
    font-weight normal
    color #41B883
    img
      width 45px
      height 45px
      margin-right 10px
    strong
      font-size 40px
      font-weight 900
      color #35495E
  h2
    color #35495E
    font-size 35px
    margin 40px 0 20px
  h3
    color #35495E
    margin 0 0 20px
    font-size 22px
  h4
    color #35495E
    margin 0 0 20px
    font-size 20px
  p, li
    font-size 18px
    color #454545
    line-height 1.5
    margin 0 0 10px
  a 
    color #35495E
    font-weight bold
    text-decoration none
    border-bottom 1px dotted #35495E
  @media all and (max-width: 900px)
    .block
      .block-text
        width 100%
        order 2
      figure
        order 1
  @media all and (max-width: 800px)
    .list
      .list-item.third
        width 100%
        margin-bottom 20px
        text-align left
    h1
      font-size 20px
      strong 
        font-size 24px
      img
        width 30px
        height 30px
        margin-right 8px
    h2
      font-size 22px
    h3
      font-size 18px
    p, li
      font-size 14px
    li
      margin-bottom 10px
    .block 
      img 
        max-width 100%
        height auto
        display block
</style>

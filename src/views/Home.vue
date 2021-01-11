<template>
  <div class="home">
    <h2 class="title">Habilidades</h2>
    <h3 class="title-2">Front-End</h3>
    <ul class="list">
      <li>
        <span class="string">HTML5</span>
      </li>
      <li>
        <span class="string">CSS3</span>
      </li>
      <li>
        <span class="string">JavaScript (ES6 e superior)</span>
      </li>
      <li>
        <span class="string">TypeScript</span>
      </li>
      <li>
        <span class="string">Sass</span>
      </li>
      <li>
        <span class="string">Stylus</span>
      </li>
      <li>
        <span class="string">Vue.js</span>
      </li>
      <li>
        <span class="string">Vuetify.js</span>
      </li>
      <li>
        <span class="string">Nuxt.js</span>
      </li>
      <li>
        <span class="string">PIXI.js</span>
      </li>
    </ul>
    <h3 class="title-2">Backend</h3>
    <ul class="list">
      <li>
        <span class="string">NodeJS</span>
      </li>
      <li>
        <span class="string">NestJS</span>
      </li>
      <li>
        <span class="string">Express</span>
      </li>
      <li>
        <span class="string">Socket.io</span>
      </li>
    </ul>
    <h3 class="title-2">Banco de dados</h3>
    <ul class="list">
      <li>
        <span class="string">MySQL</span>
      </li>
      <li>
        <span class="string">PostgreSQL</span>
      </li>
      <li>
        <span class="string">MongoDB</span>
      </li>
      <li>
        <span class="string">ArangoDB</span>
      </li>
    </ul>
    <h3 class="title-2">Mobile</h3>
    <ul class="list">
      <li>
        <span class="string">Flutter</span>
      </li>
      <li>
        <span class="string">React Native</span>
      </li>
    </ul>

    <section id="portifolio">
      <h2 class="title">Conheça alguns projetos relevantes</h2>
      <section>
        <h3 class="comment-2 portifolio-title">Pubby.club</h3>
        <p class="comment">
          Pubby.club é uma aplicação que permite usuários reproduzir músicas e
          vídeos em grupo. O sistema conta com uma fila onde os usuários entram
          e é reproduzida uma música de cada usuário. As mídias utilizadas são
          de plataformas de terceiros como Youtube e SoundCloud. Neste projeto
          utilizei Vue.js + Nuxt.js no front-end, NodeJS, PostgreSQL e Redis no
          back-end.
          <a class="link" href="https://pubby.club">Acesse agora</a>
        </p>
      </section>
      <section>
        <h3 class="comment-2 portifolio-title">SOAE Comunicação</h3>
        <p class="comment">
          SOAE é um software de gestão escolar desenvolvido pela
          <a class="link" target="_blank" href="http://linkdesign.com.br/"
            >Linkdesign Tecnologia</a
          >. Nele eu ajudei a desenvolver o módulo de comunicação que permite
          que pais ou responsáveis acompanhe o desempenho escolhar de seus
          filhos. Utilizei o framework Flutter para a criação de um Aplicativo
          para Android e IOS, Também foi utilizado Vue.js + Vuetify para a
          criação de um painel administrativo e uma versão web do aplicativo.
          <a
            class="link"
            href="https://play.google.com/store/apps/details?id=br.com.linkdesign.soae&hl=pt_BR"
            >Veja na PlayStore</a
          >
        </p>
      </section>
      <section>
        <h3 class="comment-2 portifolio-title">FamilyDoc</h3>
        <p class="comment">
          <a class="link" target="_blank" href="https://familydoc.com.br"
            >FamilyDoc</a
          >
          é um aplicativo que permite pacientes e profissionais da saúde
          realizar consultas sem sair de casa. Nele utilizei o framework React
          Native para a desenvolver os aplicativos para Android e IOS. Também
          utilizei a tecnologia WebRTC para realizar videochamadas e Vue.js +
          Vuetify no front-end das Web do aplicativo.
          <a
            class="link"
            target="_blank"
            href="https://play.google.com/store/apps/details?id=br.com.familydoc.paciente&hl=pt_BR"
            >Veja na PlayStore</a
          >
          ou
          <a
            class="link"
            target="_blank"
            href="https://paciente.familydoc.com.br"
            >Acesse a versão Web</a
          >
        </p>
      </section>
      <section>
        <h3 class="comment-2 portifolio-title">
          Open Hotel (Em desenvolvimento)
        </h3>
        <p class="comment">
          <a class="link" target="_blank" href="https://github.com/open-hotel"
            >Open Hotel</a
          >
          é um projeto pessoal de código aberto que estou desenvolvendo, minha
          ideia é desenvolver um remake do jogo Habbo utilizando tecnologias
          modernas sem depender do Adobe Flash Player para a execução. Nele
          estou utilizando a linguagem TypeScript, a biblioteca PIXI.js para
          renderização do jogo no canvas, e o framework Vue.js para a interface
          do usuário.
          <a
            class="link"
            target="_blank"
            href="https://structure-migration--open-hotel-demo.netlify.app/"
            >Acesse agora</a
          >
        </p>
      </section>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

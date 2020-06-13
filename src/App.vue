<template>
  <div id="app">
    <img
      class="profile-photo"
      src="https://github.com/salomaosnff.png"
      alt="Salomão Neto"
    />
    <div class="top center">
      <h1 class="profile-name mustache">Salomão Neto</h1>
      <p class="comment center">Desenvolvedor Web Fullstack</p>
    </div>
    <div class="center">
      <a class="link" target="_blank" href="https://github.com/salomaosnff"
        >https://github.com/salomaosnff</a
      ><br />
      <a class="link" target="_blank" href="mailto:salomaosnff3@gmail.com"
        >salomaosnff3@gmail.com</a
      ><br />
      <a href="https://t.me/salomaosnff" target="_blank" class="link"
        >Me chama no Telegram</a
      >
    </div>
    <div id="content">
      <router-view />
    </div>
  </div>
</template>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: "Fira Code", monospace;
  background: #1e1e1e;
  color: #e0e0e0;
  padding: 1em;
}

.profile-name {
  font-size: 1.618em;
}

.top {
  position: sticky;
  top: 0;
  background: linear-gradient(to bottom, #1e1e1e 30%, transparent 100%);
  padding: 0.5em 0;
}

.comment {
  color: #aaaaaa;
  margin: 1em 0;

  &:before {
    content: "/** ";
  }

  &:after {
    content: " **/";
  }
}

.comment-2 {
  color: #628c4f;
  margin: 1em 0;

  &:before {
    content: "// ";
  }
}

.portifolio-title {
  margin-top: 2em;
}

.string {
  color: #ce9178;
  &:before {
    content: '"';
  }
  &:after {
    content: '"';
  }
}

.list {
  list-style: none;

  &:before {
    content: "[";
  }
  &:after {
    content: "]";
  }

  li {
    margin-left: 1em;
    &:after {
      content: ",";
    }
  }
}

.link {
  color: #0088dd;
  font-weight: bold;
  text-decoration: none;
  &:before {
    content: "[";
  }
  &:after {
    content: "]";
  }

  &:hover {
    text-decoration: underline;
  }
}

.title,
.title-2 {
  color: #569cd6;
  margin: 2em 0 1em 0;
}

.title:before {
  content: "# ";
}
.title-2:before {
  content: "## ";
}

.inline {
  display: inline-block;
}

#left {
  background: #2b2b2b;
  text-align: center;
  padding: 1em;
  width: 100%;
}

.profile-photo {
  display: block;
  width: 150px;
  height: 150px;
  border-radius: 100%;
  margin: 0 auto 1em auto;
}

.mustache {
  &::before,
  &::after {
    color: #569cd6;
  }
  &:before {
    content: "{{ ";
  }
  &:after {
    content: " }}";
  }
}

.tag {
  &:before {
    content: "<";
  }
  &:after {
    content: " />";
  }
}

.center {
  text-align: center;
}

#content {
  max-width: 768px;
  margin: 0 auto;
}
</style>

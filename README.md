## Olá, Pessoal!!

Tenho 20 anos, moro em Salvador/bahia e sou apaixonado por programação! Sou aventureiro no universo da programação, criador oficial de bugs, e quanto mais eu aprendo e passo raiva, mais eu amo tudo isso e percebo que estou no caminho certo!  

<p align="center">
  <img src="https://super.abril.com.br/wp-content/uploads/2016/09/super_imggato_digitando_0.gif" width="350">
</p>

### 🖥️ Tecnologias e Ferramentas: 

<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" title = "HTML5"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" title = "CSS3"/></code>
<code><img alt="Lucas-Python" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"></code>
 <img src="https://www.cdnlogo.com/logos/c/76/c.svg" alt="c++" width="40px"/> </a>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title = "JAVASCRIPT"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title = "GIT"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title = "GITHUB"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" title = "JAVA"/></code>

</br>
</br>
<div display="inline-block">
 <p align="left">🤿 Faço parte da Unijorge (faculdade) </a>;</p>
 <p align="left">📚 Tenho estudado Java, python e iniciei meus estudos para melhor em opencv para reconhecimento facial;</p>
 <p align="left">☕🎮 só acordo com café, adoro games e faço piadas ruins com certa frequência.</p>
</div>



</br>

📫 Você pode falar comigo pelo [Discord](https://discord.gg/9mVvF66CVW) este é um servidor que utilizo para ajudar as pessoas da minha faculdade. (eu demoro a responder as vezes, mas respondo pode confiar ) e pode conhecer meus projetos já desenvolvidos, que estão disponíveis aqui nos repositórios.

</br>
##
<p align="center">
<a href="https://github.com/Nicholaszin">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Nicholaszin&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Nicholaszin&layout=compact&langs_count=8&theme=algolia"/>
</a>
</p>

<div align="center">
  <a href="https://github.com/Platane/snk">
    <img src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" alt="Jogo da cobrinha no GitHub" />
  </a>
</div>



























Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

**github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

If you are only interested in generating a svg, consider using this faster action: `uses: Platane/snk/svg-only@v3`

**dark mode**

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

**interactive demo**

<a href="https://platane.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://platane.github.io/snk)

**local**

```
npm install

npm run dev:demo
```

## Implementation

[solver algorithm](./packages/solver/README.md)

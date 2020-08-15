<h1 align="center">Contribution</h1>

<p>
    Para adicionar uma amostra da sua config você pode fazer um pull request utilizando utilizando os templates abaixo. O processo é bem simples, basta apenas copiar e colar o template desejado no final da sessão <b>dotfiles | scripts | bars</b> no arquivo <a href="https://github.com/hiukky/unixwmbr/blob/master/README.md">README.md</a> e alterar os locais indentificados com <b>{ instrução }</b> pelo valor correto.
</p>

<h4>Examplo:</h4>

Para adicionar o link do repositorio dotfiles, altere o exemplo abaixo:

```html
<a href="{Link referencia para o seu dotfiles.}" />
```

Para:

```html
<a href="https://github.com/dotfiles" />
```

<h3 align="center">Template Dotfiles</h3>

```html
<div align="center">
  <a href="{Link referencia para o seu dotfiles.}">
    <img
      alt="Dotfiles"
      src="https://img.shields.io/badge/config-{seu nome}-%232c3e50?style=for-the-badge"
    />
  </a>
  <a href="{Link referencia para WM.}">
    <img
      alt="WM"
      src="https://img.shields.io/badge/wm-{nome da wm}-%235352ed?style=for-the-badge"
    />
  </a>
  <a href="{Link referencia para o thema.}">
    <img
      alt="Theme"
      src="https://img.shields.io/badge/theme-{nome do thema}-%232ed573?style=for-the-badge"
    />
  </a>
  <br /><br />
  <img alt="Screenshot" src="{Link para captura de tela / Gif}" />
</div>
```

<h3 align="center">Template Scripts / Bars</h3>

```html
<div align="center">
  <a href="{Link referencia para o seu script.}">
    <img
      alt="Script"
      src="https://img.shields.io/badge/{nome do script}-%2322252f?style=for-the-badge"
    />
  </a>
  <br /><br />
  <p>
    {adicione um texto falando sobre o script, ao menos o que ele faz imagem ou
    gif de amostra, se houver}
  </p>
  <img alt="Screenshot" src="{Link para captura de tela / Gif}" />
</div>
```

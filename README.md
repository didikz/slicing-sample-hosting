## About

As a backend engineer, I am interested with Utility-First of Tailwind CSS. This make me gain more understanding about building a web page with simple setup without write bunch of CSS script.

Here we go as a result, I've built a simple homepage of Hosting Service based on design [BeServer - Landing Page](https://dribbble.com/shots/9951239%E2%81%A0) from [Muh Salmon](https://dribbble.com/muhsalmon). Used stacks are:

+ [Tailwind CSS](https://tailwindcss.com/)
+ [Tailwind UI](https://tailwindui.com/documentation)
+ [Autoprefixer](https://github.com/postcss/autoprefixer)
+ [PostCSS CLI](https://github.com/postcss/postcss-cli)
+ [Font Awesome](https://fontawesome.com/)
+ [UnDraw Illustration](https://undraw.co/illustrations)

## Installation & Build

```bash
$ npm install && npm build
```

Always run `npm build` if you modify your `tailwind.config.js` or adding your custom css.

## Run

For hot reload, you may use `live-server` tool.

```bash
$ npm install -g live-server
```

run command inside project directory where your `index.html` is exists.

```bash
$ live-server public
```
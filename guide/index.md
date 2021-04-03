[windi css]: https://github.com/windicss/windicss
[tailwind css]: https://tailwindcss.com/docs
[discussions]: https://github.com/windicss/windicss/discussions
[GitHub Issues]: https://github.com/windicss/windicss/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc
[GitHub Discussions]: https://github.com/windicss/windicss/discussions
[utilities reference]: /utilities/
[utilities]: /utilities/
[directives]: /guide/directives

# Getting Started

::: tip
We are working on a fresh new docs with major docs rewrites and some pretty cool [interactive playgrounds](https://twitter.com/antfu7/status/1371779599084888064?s=20), stay tuned!
:::

If you are interested to learn more about Windi CSS before trying it, check out the [Introduction](./introduction).

If you are looking for utilities, check out the [utilities reference].

## Integrations 💿

| Frameworks | Package | Version |
| :-- | :-- | :-- |
| CLI | [Built-in](https://windicss.org/guide/cli) | ![](https://img.shields.io/npm/v/windicss?label=&color=0EA5E9) |
| VSCode Extension | [windicss-intellisense](https://github.com/windicss/windicss-intellisense) | ![](https://img.shields.io/visual-studio-marketplace/v/voorjaar.windicss-intellisense.svg?label=&color=1388bd) |
| Vite | [vite-plugin-windicss](https://github.com/windicss/vite-plugin-windicss) | ![](https://img.shields.io/npm/v/vite-plugin-windicss?label=&color=0EA5E9) |
| Rollup | [rollup-plugin-windicss](https://github.com/windicss/vite-plugin-windicss/tree/main/packages/rollup-plugin-windicss) | ![](https://img.shields.io/npm/v/rollup-plugin-windicss?label=&color=1388bd) |
| Webpack | [windicss-webpack-plugin](https://github.com/windicss/windicss-webpack-plugin) | ![](https://img.shields.io/npm/v/windicss-webpack-plugin?label=&color=1388bd) |
| Vue (Webpack) | [vue-windicss-preprocess](https://github.com/windicss/vue-windicss-preprocess) | ![](https://img.shields.io/npm/v/vue-windicss-preprocess?label=&color=0EA5E9) |
| Nuxt | [nuxt-windicss](https://github.com/windicss/nuxt-windicss-module) | ![](https://img.shields.io/npm/v/nuxt-windicss?label=&color=1388bd) |
| Svelte | [svelte-windicss-preprocess](https://github.com/windicss/svelte-windicss-preprocess) | ![](https://img.shields.io/npm/v/svelte-windicss-preprocess?label=&color=1388bd) |

## Usage 🚀

Windi CSS provides all [utilities] in [Tailwind CSS], so usage is very [similar][tailwind css].

You can use utility classes in your components and stylesheets as usual:

```html
<div class="py-8 px-8 max-w-sm mx-auto bg-white rounded-xl shadow-md space-y-2 sm:py-4 sm:flex sm:items-center sm:space-y-0 sm:space-x-6">
  <img class="block mx-auto h-24 rounded-full sm:mx-0 sm:flex-shrink-0" src="/img/erin-lindford.jpg" alt="Woman's Face" />
  <div class="text-center space-y-2 sm:text-left">
    <div class="space-y-0.5">
      <p class="text-lg text-black font-semibold">Erin Lindford</p>
      <p class="text-gray-500 font-medium">Product Engineer</p>
    </div>
    <button class="px-4 py-1 text-sm text-purple-600 font-semibold rounded-full border border-purple-200 hover:text-white hover:bg-purple-600 hover:border-transparent focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-offset-2">
      Message
    </button>
  </div>
</div>
```

[Directives] are also supported:

```css
.btn {
  @apply font-bold py-2 px-4 rounded;
}

.btn-blue {
  @apply bg-blue-500 hover:bg-blue-700 text-white;
  padding-top: 1rem;
}
```

## Contact ✉️

Please visit [GitHub Issues] to report bugs you find, and [GitHub Discussions] to make feature requests, or to get help.

Don't hesitate to [⭐️ star the project][Windi CSS] if you find it useful!

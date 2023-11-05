---
title: Translating the docs.
description: Docs for translating the docs.
---

If you want to contribute towards Cosmos Cloud, a good way to do that is to translate the wiki. This can help people that do not speak or not know how to read English, be able to read the Cosmos Docs in their own language.

## Getting setup

To get started on translating the wiki, you need to have a local environment ready for testing your translations. This can be done by following the steps shown in the [README](https://github.com/azukaar/Cosmos-Doc#installing).

Before getting started, you have to add the translation you are doing to the `astro.config.mjs` file. This can be done by:

1. Open `astro.config.mjs`
2. Add a new entry below line **26**
3. Use the template below to add a new entry and fill out the details for the language you are translating.

```
        <short-langauge-name>: {
          label: '<language-name>',
          lang: '<short-langauge-name>',
        },
```

5. Replace the blockquotes with the required details for the language you are translating.
6. Finally, test in a local enviornment using `npm run dev` in the terminal to see if you can see your language in the dropdown menu.

## Creating folders

The first step to translating the wiki is creating a new folder in the docs directory so the original docs is separate from the translated docs. To do this:

1. Go to `src/content/docs/`
2. Create a new folder with your language name / internationalization name.

After this is done, you can start translating the docs from English to the language that you are translating to.

If you need any help / support, don't hesitate to ask in the [Cosmos Discord](https://discord.gg/PwMWwsrwHA), and we can help you out from there.
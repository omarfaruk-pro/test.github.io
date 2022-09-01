# Dusk Flex Theme Template

[Getting started](#getting-started) |
[New code submission](#new-code-submission) |
[License](#license)

## Getting started

Dusk Flex Theme Template represents a HTML-first, Bootstrap 5 and jQuery/JavaScript-only-as-needed approach to theme development. It's Shopify's first source available theme with performance, flexibility, and [Online Store 2.0 features](https://www.shopify.com/partners/blog/shopify-online-store) built-in and acts as a reference for building Shopify themes.

Say you're building a new template section off dusk flex template but you still want to be able to pull in the latest changes, you can add a remote `upstream` pointing to this dusk flex template repository.

1. Navigate to your local template folder.
2. Verify the list of remotes and validate that you have both an `origin` and `upstream`:

```sh
git remote -v
```

3. If you don't see an `upstream`, you can add one that points to dusk flex template repository:

```sh
git remote add upstream https://github.com/Limonrana/dusk-flex-theme-template.git
```

4. Pull in the latest dusk flex template changes into your repository:

```sh
git fetch upstream
git pull upstream main
```

## New code submission

Ensure that push the new code create an new branch with your task name. EX: limon-task-1

- **Download Or Pull the code before start project**
- **Please use the hypen and prefix (WS--) for class name. EX: ws--heading-h1**
- **Please use the flickity for carousel or slider [Flickity](https://flickity.metafizzy.co/#getting-started)**
- **Please make sure every section is responsive**
- **Finaly, before push the code, please create an new branch with task name. EX: limon-task-1**

## License

Copyright (c) 2022-present Web Soft King LTD.

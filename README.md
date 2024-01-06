# substack-redirect
example redirect for substack custom domain (`/ -> www.*`), using free static site hosting and a `_redirects` file

`_redirects` file valid for [netlify](https://www.netlify.com/) ([docs](https://docs.netlify.com/routing/redirects/redirect-options/)) and [codeberg pages](https://codeberg.page/) ([docs](https://docs.codeberg.org/codeberg-pages/redirects/))

## quickly deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/pharmacologic/substack-redirect)

you will want to edit `_redirects` to reflect your actual URL

for a maybe less corporate option, you could fork [this repository](https://codeberg.org/pharmacologic/substack-redirect) on codeberg to use with [codeberg pages](https://codeberg.page)

## dns

you will also need to configure DNS so that the root (apex) of your domain is pointing to your static site host

https://docs.netlify.com/domains-https/custom-domains/configure-external-dns/

https://docs.codeberg.org/codeberg-pages/using-custom-domain/


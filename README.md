# substack-redirect
example redirect for substack custom domain (`/ -> www.*`), using free static site hosting and a `_redirects` file

`_redirects` file valid for [netlify](https://www.netlify.com/) ([docs](https://docs.netlify.com/routing/redirects/redirect-options/)) and [codeberg pages](https://codeberg.page/) ([docs](https://docs.codeberg.org/codeberg-pages/redirects/))

## quickly deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/pharmacologic/substack-redirect)

you will want to edit `_redirects` to reflect your actual URL

## dns

you will also need to configure DNS so that the root of your domain is pointing to your static site host

note: using a custom domain with netlify requires you to use their nameservers for your domain, so you will have to recreate a `www` DNS record for your substack newsletter in the netlify domain settings

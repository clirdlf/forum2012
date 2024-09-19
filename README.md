# Forum 2012
 based on 
https://web.archive.org/web/20121213011852/http://www.diglib.org/forums/2012forum/

```
RedirectMatch 301 ^/dlf-events/2012forum/(.*)$ https://forum2012.diglib.org/$1
```

## Notes

Keynote recording does not exist on Vimeo or YouTube

404s

* https://www.diglib.org/community/collaborations/mets/ 
* http://www.diglib.org/community/collaborations/curatecamp/

# 11ty with Bootstrap Scaffold

This is scaffold for new projects using [11ty](https://www.11ty.dev/) with [Bootstrap](https://getbootstrap.com/docs/5.3/examples/) (building with [Vite](https://vitejs.dev/)) meant to deploy to [GitHub Pages](https://pages.github.com/). Also includes some basic [VSCode](https://code.visualstudio.com/) setup.

* [Bootstrap 5](https://getbootstrap.com/docs/5.3/customize/sass/)
* [Bootstrap Icons](https://icons.getbootstrap.com/)
* [Vite](https://vitejs.dev/)
* [Pagefind](https://pagefind.app/)

## Eleventy Plugins

* [@11ty/eleventy-img](https://www.11ty.dev/docs/plugins/image/)
* [@11ty/eleventy-navigation](https://www.11ty.dev/docs/plugins/navigation/)
* [@11ty/eleventy-plugin-rss](https://www.11ty.dev/docs/plugins/rss/)
* [@11ty/eleventy-plugin-syntaxhighlight](https://www.11ty.dev/docs/plugins/syntaxhighlight/)
* [@11ty/eleventy-plugin-vite](https://www.11ty.dev/docs/server-vite/)

## Demo

<https://waynegraham.github.io/eleventy-plus-bootstrap-scaffold/>

# Usage

## Install

    npm install

## Start local development

    npm start

Preview runs at <http://localhost:8080>

## Build

    npm run build

# Credits

* Layout based on Bootstrap [Jumbotron Example](https://getbootstrap.com/docs/5.3/examples/jumbotron/)


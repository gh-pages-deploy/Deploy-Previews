# Deploy Previews

This repository is used to host pages for deploy previews from Pull requests.

## Structure

The structure you find on the [`gh-pages` branch][gh-pages] is as follows:

```
<root>
  |
  |- <user|org>/<repository>
       |
       |- <pull_request.number>
```

This means that every preview for pull requests in `Andre601/blog` will be hosted under `Andre601/blog/<pull_request.number>/` on the [`gh-pages` branch][gh-pages].

## Contact

This repository is maintained by [Andre601][andre601]. Please contact him for any questions you may have.

[gh-pages]: https://github.com/gh-pages-deploy/Deploy-Previews/tree/gh-pages
[andre601]: https://github.com/Andre601

# Jekyll on ZEIT Now

This directory is a brief example and starter app for [Jekyll](https://jekyllrb.com/), ready to deploy on [ZEIT Now](https://zeit.co/now).

To get started with this project yourself, use the following command from [Now CLI](https://zeit.co/docs/v2/getting-started/installation#now-cli):

```shell
$ now init jekyll
```

> Alternatively, create a project, and Git repository, with this example template [using the ZEIT dashboard](https://zeit.co/new/jekyll).

Once initialized locally, you can use the [Jekyll CLI](https://jekyllrb.com/docs/) to start a local development server so you can work on your new Jekyll site:

```shell
$ jekyll serve
```

> Note: Make sure to install the jekyll and bundler gems with `gem install jekyll bundler` in your terminal, then you can install the dependencies before running your development server for the first time with `bundle exec jekyll serve`.

To [deploy](https://zeit.co/docs/v2/deployments/basics) this application, with [Now installed](https://zeit.co/docs/v2/getting-started/installation), run the following from your terminal:

```shell
$ now
```

Alternatively, your new Jekyll site can be automatically deployed and aliased using [Now for GitHub](https://zeit.co/docs/v2/integrations/now-for-github) or [Now for GitLab](https://zeit.co/docs/v2/integrations/now-for-gitlab). Pushing these files to a new repository with a `now.json` file in the root, and with either [Now for GitHub](https://zeit.co/docs/v2/integrations/now-for-github) or [Now for GitLab](https://zeit.co/docs/v2/integrations/now-for-github) configured for that repository, your site will be automatically deployed for every push and pull/merge request, and aliased for every push to the default branch!

## Included In This Starter

This starter project includes:
- A fresh Jekyll app using the [Jekyll CLI](https://jekyllrb.com/docs/usage/) (with a few edits to provide resources!)
- A pre-defined `build.sh` shell script that installs Ruby through `rbenv`, the dependencies (including Jekyll), then builds the app to the default `_site` output directory.
- A pre-configured `now.json` file that uses the aforementioned build shell script and deploys the `_site` directory when built.

## Resources

For more resources on how to configure your new Jekyll site to do more with Now or to deploy any other kind of application, see the following:

- [New to Now? Get a quick introduction](https://zeit.co/docs/v2/getting-started/introduction-to-now)
- [Learn the basics of deployment on Now](https://zeit.co/docs/v2/deployments/basics)
- [Learn how to configure your Now deployments](https://zeit.co/docs/v2/deployments/configuration)
- [Learn how to configure Now Routes for redirects, caching, and more](https://zeit.co/docs/v2/deployments/routes)
- [Learn how to alias your deployment to a domain or other unique shareable URLs](https://zeit.co/docs/v2/domains-and-aliases/introduction)

For more information on Jekyll itself, [see their documentation](https://jekyllrb.com/docs/).


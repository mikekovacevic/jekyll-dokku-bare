# What is this?

This is a barebone repository for using Jekyll with [Dokku](https://github.com/progrium/dokku)

I've forked [Dokku](https://github.com/rodeva/dokku) and the [Buildstep](https://github.com/rodeva/buildstep) to enable the custom heroku buildpack from [Matt Manning](https://github.com/mattmanning/heroku-buildpack-ruby-jekyll)

Install Dokku using the bootstrapping script from my repository. This is best done on a fresh VPS running Ubuntu > 13.04 x64

Then clone this repository, and push using

```bash
git remote add NAME git@[HOSTNAME]:[PROJECT]
git push NAME master
```

You'll have a fresh Jekyll installation running neatly inside a Docker container powered by Dokku.

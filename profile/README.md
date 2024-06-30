# About

b-data is a company specialised in Data Science services on GPU accelerated
computing infrastructure.  

As advocates of open-source software (OSS), we sponsor

* the [QGIS](https://qgis.org/en/site/about/sustaining_members.html) project,
* the [Julia](https://github.com/sponsors/julialang) language,
* the [R Foundation](https://www.r-project.org/foundation/) and
* the [FreeBSD Foundation](https://www.freebsdfoundation.org/).

We devote about 20% of our time to OSS and maintain

* [dev containers](https://containers.dev),
* [docker images](https://docs.docker.com/guides/docker-concepts/the-basics/what-is-an-image/)
  and
* deployment templates

for Data Scientists, ML/AI Engineers, and the like 🧑‍💻.

We provide [Data Science dev containers](https://github.com/b-data/data-science-devcontainers)
for use with
[VS Code](https://code.visualstudio.com/docs/devcontainers/containers) (local/'remote SSH') and
[GitHub Codespaces](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository?tool=webui#creating-a-codespace-for-a-repository) (web browser).  

* 🎯 A unified IDE for the Data Science programming languages
  [R](https://www.r-project.org), [Python](https://www.python.org),
  [Julia](https://julialang.org) and [Mojo](https://www.modular.com/max/mojo).
* 🔥 Most images are also available in a GPU accelerated
([`nvidia/cuda`](https://hub.docker.com/r/nvidia/cuda)-based) version.

**Our credo: Self-host your Data Science software stack**; based on
[Træfik](https://github.com/b-data/docker-deployment-traefik),
[GitLab](https://github.com/b-data/docker-deployment-gitlab-ce) and
[Jupyter](https://github.com/b-data/docker-deployment-jupyter)
([JupyterLab](https://jupyter.org) +
[code-server](https://github.com/coder/code-server)).

Here you can find everything you need – for free! 🔬 Check it out at <https://demo.jupyter.b-data.ch>.

![Screenshot](https://raw.githubusercontent.com/b-data/jupyterlab-r-docker-stack/main/assets/screenshot.png)

---

Besides, see Olivier's ([benz0li](https://github.com/benz0li)'s) work on
[GHC musl](https://github.com/benz0li/ghc-musl) – Unofficial binary
distributions of GHC on Alpine Linux.  
ℹ️ The multi-arch (`linux/amd64`, `linux/arm64/v8`) docker image used to build
the *statically linked* Linux amd64 and arm64 binary releases of
[Pandoc](https://github.com/jgm/pandoc).

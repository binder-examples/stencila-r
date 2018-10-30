# stencila-r

Demo for Stencila &amp; DAR on binder with [R](https://www.r-project.org/) code.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/nuest/stencila-r/master)

Learn more about [Stencila](https://stenci.la/) and it's integration with [Binder](https://mybinder.org/) in this blog post: [TODO](TODO)

`repo2docker` automatically picks up if there is a `*.jats.xml` file in a repository which has code chunks with language `"r"` and then installs and configures the required software (`stencila` R package, `nbstencilaproxy`).

You can also add a `runtime.txt` file and or an `install.R` file as defined [in the repo2docker docs](https://repo2docker.readthedocs.io/en/latest/config_files.html#runtime-txt-specifying-runtimes).

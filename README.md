# Denmark's Riso Association

To update the website locally you will need a text editor and a command line. If you get [VSCode](https://code.visualstudio.com/), you can have access to both in the same window, which might be easiest!

This website is built with a tool called [`zola`](https://www.getzola.org/)
- a static site generator. We currently use version `0.16.1`.

You can install it on a Mac with `brew` package manager from your command line by pasting this,

```bash
brew install zola
```

and on windows with `scoop` package manager by pasting this,

```powershell
scoop install zola
```

You can run a local build of the website with (also in your command line):

```bash
zola serve
```

The local build is available at `http://127.0.0.1:1111`, which you can just paste in your browser and check out your changes.

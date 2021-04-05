---
permalink: /MathInMD/
title: "Math In MD"
excerpt: "Math In MD"
author_profile: true
---

<!-- https://github.com/zlatanvasovic/zlatanvasovic.github.io/edit/gh-pages/blog/2020/06/make-your-julia-package.md -->


Suppose you came up with the formula to calculate n-th term of the famed Fibonacci series.
Using $ {\varphi = \frac{1 + \sqrt{5}}{2}} $, it turned out to be:
$$ \frac{\varphi^n - (-\varphi)^{-n}}{\sqrt{5}} $$

You want to share it with the world.

## Using a template

It also requires you to have `user.name`, `user.email` and `github.user` set in `.gitconfig`.
If those are missing, you can add them like `git config --global user.name "username"`, executed in your shell.

Now you can make your own package "Fibonacci" based on a simple template. In Julia REPL:
```julia
julia> using PkgTemplates
julia> t = Template()
julia> t("Fibonacci")
```
Voila! Your package is in `~/.julia/dev/Fibonacci` (the default location).
Navigate to it.
You can see the metafiles like `Project.toml`, `.gitignore`, `LICENSE` and `README.md` already created.




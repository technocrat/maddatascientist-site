# Mad Data Scientist

Source for https://maddatascientist.io, built with [Calepin](https://vincentarelbundock.github.io/calepin) (Typst).

```
calepin compile . public    # build
npx wrangler deploy         # publish public/ to Cloudflare
```

Posts go in `posts/*.typ`. Pushing to GitHub does not update the live site; `wrangler deploy` does.

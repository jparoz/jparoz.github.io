# jparoz.github.io

## Deploying changes
Make the desired changes on the `main` branch,
running `npm run build` before committing.
Once you've committed everything you need,
use the following command to deploy to Github Pages:

```sh
git subtree push --prefix build origin gh-pages
```

This will trigger the deployment process.

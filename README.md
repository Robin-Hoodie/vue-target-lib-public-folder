# sandbox

Run `yarn build --target lib`

Expected:

`public-images/public-image.png` is copied over to the `dist/` folder, just as running `vue-cli-service build` without a `target` argument does.

Result:

Nothing in the `public` directory is copied

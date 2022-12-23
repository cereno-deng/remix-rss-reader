# Remix RSS Reader

### Development

```sh
yarn dev
```

### Deployment

```sh
yarn build
```

Make sure to deploy the output of `remix build`
- `build/`
- `public/build/`

```sh
npm start
```

### Change Hosting Settings

When you ran `npx create-remix@latest` there were a few choices for hosting. You can run that again to create a new project, then copy over your `app/` folder to the new project that's pre-configured for your target server.

```sh
cd ..
# create a new project, and pick a pre-configured host
npx create-remix@latest
cd new-remix-rss-reader
# remove the new project's app
rm -rf app
# copy your app over
cp -R ../remix-rss-reader/app app
```

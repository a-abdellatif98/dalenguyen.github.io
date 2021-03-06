# Dale Nguyen Portfolio Website

This project was generated with Angular 8 and published to Github Pages.

This project will host on two places:

- Github Pages: https://dalenguyen.github.io
- Heroku: http://dalenguyen.me (Server Side Rendering & SEO support)

## Development server

Run `npm run dev` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Publish to Github page

Deploy based on branch master

```sh
npm run deploy:web
```

## Update sentry

After deploying new feature or fix a bug. The Sentry release should be updated.

```sh
sh sentry-release.sh
```

## Angular Universal

For Development

```sh
npm run dev:ssr
```

For Production

```sh
npm run start:ssr
```

## Contribution

Any contribution to this project are welcome. Please read the [contribution guideline](https://github.com/dalenguyen/dalenguyen.github.io/blob/dev/CONTRIBUTING.md)

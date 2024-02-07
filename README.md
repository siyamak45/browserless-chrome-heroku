# browserless/chrome for Heroku

Deploy [browserless/chrome](https://github.com/browserless/chrome) for websites testing in one click

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Inzhenerka/browserless-chrome-heroku)

## Configuration

-   [Docker Configuration](https://www.browserless.io/docs/docker)

## Use with playwright

Add this to `use` field of your Playwright configuration (`playwright.config.ts` file):

``` typescript
    connectOptions: {
      wsEndpoint: 'wss://<your-app-id>.herokuapp.com/playwright'
    }
```

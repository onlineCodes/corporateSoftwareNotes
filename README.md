# corporateSoftwareNotes

just a public Wiki for some Information to share with volunteer and team members of CS

For usage read [Shower Presentation Template](template.md).

## Quick Start with Hosting

you can build a clean copy of your slides:

```sh
npm run bundle
```

You’ll find your presentation in `bundled` folder. You can also run `npm run archive` to get the same files in `presentation.zip`.

Publish your presentation online by running:

```sh
npm run publish
```

You’ll have your slides published to `https://USER.github.io/REPO/`.

## Deploy to Netlify

By clicking the button below you can fork this repo and deploy it to Netlify.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/onlineCodes/corporateSoftwareNotes)

By doing this you would get a GitHub repo linked with Netlify in a way any change to the repo would trigger a Shower rebuild and deploy to Netlify servers, which allows for an easy way to create and share Shower presentation without the need to install anything locally.


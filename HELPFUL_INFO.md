Quick Start - Contentful & Next.js:

https://vercel.com/guides/integrating-next-js-and-contentful-for-your-headless-cms

mkdir cms-contentful-app
cd cms-contentful-app
npx create-next-app --example cms-contentful .

npx cross-env CONTENTFUL_SPACE_ID=n9y5oy6ac8pa CONTENTFUL_MANAGEMENT_TOKEN=CFPAT-yB68Aro_rNEOVtQ3KojdQPuAhGf4tsSUCaGbPFCuu_0 npm run setup

“Historically, developers had to use different languages (e.g. JavaScript, PHP) and frameworks when writing code for the server and the client.

With React, developers can use the same language (JavaScript), and the same framework (e.g. Next.js or your framework of choice). This flexibility allows you to seamlessly write code for both environments without context switching.”

Setting Up Preview Site

https://<YOUR_VERCEL_URL>/api/draft?secret=<CONTENTFUL_PREVIEW_TOKEN>&slug={entry.fields.slug}

Setting up Live Updates

https://www.contentful.com/developers/docs/tutorials/general/live-preview/#set-up-live-updates

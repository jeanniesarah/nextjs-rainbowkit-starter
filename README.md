# Next.js + Rainbow Kit Starter

This is a [Next.js](https://nextjs.org/) + [Rainbow Kit](https://www.rainbowkit.com/) starter.

## Requirements

- Node 10+
- Yarn (or NPM if you prefer)
- You will need an Alchemy account to access the Alchemy API. If you don't have one yet, sign up [here](https://www.alchemy.com/).

## Getting Started

After cloning the repository you can run `yarn` to install the dependencies. 

Then, create `.env` file
```
touch .env
```
Inside `.env`, set this variable:
```
ALCHEMY_ID=your_alchemy_application_id
```
Then start the application with `yarn dev`.

```bash
$ git clone https://github.com/jeanniesarah/nextjs-rainbowkit-starter.git
$ yarn
$ yarn dev
```

You are now able to view the application at http://localhost:3000 🎉

![nextjs-rainbowkit-starter-screenshot](https://user-images.githubusercontent.com/39424571/169580344-502be4ac-6613-470f-8c6e-1b24e49ddf0e.png)

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.


## Learn More

To learn more about Rainbow Kit, take a look at the following resources:

- [Rainbow Kit Documentation](https://rainbowkit.com/docs/introduction) - learn about Rainbow Kit features.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

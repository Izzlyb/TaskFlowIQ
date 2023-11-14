This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Creating path convention when using the App router and the app sub-directory structure

###  create 
app/example/page.tsx
    the tsx file does not have to be called page.tsx. 

    but if you name it Create.tsx the name of the main function in the file would be name CreatePage.

    you can visit the page by: 3000/example

### a dynamic path:
  app/users/[id]/page.tsx
  the function inside the file would be IdPage().

    you can get the function IdPage  by: 3000/users/123

### grouping path:
  app/(test)/monster/page.tsx.

    you can get to the function MunsterPage by: 3000/monster

  
### To import fonts into your application:
first import localFont from next/font/local 
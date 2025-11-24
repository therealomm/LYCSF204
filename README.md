This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

******************************************************************************************************************

The proposed system, PhishGuard, is designed to help users identify whether an email or SMS message is Phishing, Spam, or Safe. The system takes the message text as input and analyzes its words, structure, and any links included in it. Instead of relying on fixed keyword lists or manual checking, the system uses Machine Learning so that it can learn the patterns commonly found in phishing messages and detect new ones that may not match old keywords.
The text is detected by passing to an SVM (Support Vector Machine) classifier, which has been trained on real examples of phishing and safe messages. The SVM predicts the class of the message and also generates a confidence score showing how certain the system is about the prediction.
***********************************************************************************************************************************************************************************************
OUTPUT SCREENSHOTS

<img width="624" height="301" alt="image" src="https://github.com/user-attachments/assets/100ac886-f74e-448f-ac09-6adb945aaf2a" />
<img width="720" height="348" alt="image" src="https://github.com/user-attachments/assets/488e192d-f39b-426b-addc-ad6fc67c12b3" />
<img width="720" height="348" alt="image" src="https://github.com/user-attachments/assets/956e2cc4-4d2d-4c13-8dc1-e3c120fb5408" />
<img width="734" height="355" alt="image" src="https://github.com/user-attachments/assets/8363a85f-ebe3-411e-b0c6-aa4f5a743809" />
<img width="709" height="344" alt="image" src="https://github.com/user-attachments/assets/fe062ab9-838e-4877-86e1-086303dccd95" />
<img width="700" height="339" alt="image" src="https://github.com/user-attachments/assets/d61a93e4-5689-47a1-a783-31a143afdfbf" />


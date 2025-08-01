## Culina Share

A recipe app with the ability to save, share and discover recipes from various cuisines. (an assignment for internship)

![preview](https://github.com/user-attachments/assets/96dcb9ed-4dfb-4c99-9b56-00c4f81349e9)

## Create you own food

![preview](https://github.com/user-attachments/assets/c901c534-f04b-404b-83d6-efcbc486d1fd)

## Tech stack

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Mongoose](https://mongoosejs.com/)
- [Clerk](https://clerk.com/)

## Features

- Authentication
- Explore recipes
- Search recipes
- Filter recipes
- Trending recipes
- Save your favorite recipes
- Share your recipes

## How to setup localy

- Fork the repo
- Clone the forked repo

```bash
git clone https://github.com/MeAkash77/Culina-Share.git
```

- Install dependencies

```bash
npm install
```

- Setup clerk and mongodb environment variables

```bash
MONGO_URI=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
```

- Start the server

```bash
npm run dev
```

- Open `http://localhost:3000` in your browser

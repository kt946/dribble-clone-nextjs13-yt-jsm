# Dribbble Clone with Next.js, NextAuth.js, Tailwind CSS, Cloudinary, TypeScript

## Description

This project is a Dribbble-inspired platform that allows developers to showcase their projects and connect with the developer community. It was built using a YouTube tutorial by [JavaScript Mastery](https://www.youtube.com/watch?v=MJzmZ9qmdaE).

Welcome to the Full Stack Dribbble Clone! Developed with Next.js, Next Auth, Tailwind CSS, Cloudinary, TypeScript, JWT, GraphQL, Grafbase, and HeadlessUI, this project offers a dynamic and visually captivating experience for developers. Users can sign in with their email, upload project details, including images, titles, and descriptions, explore other developers' profiles, and easily sort through projects by category. With secure authentication, responsive design, and GraphQL-powered data retrieval, this application encapsulates the core elements of a modern developer portfolio and collaboration platform.

⭐ Note: The database may become inactive if the app is not used for a while. If this happens, please contact me and I will reactivate the database.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Links](#links)
- [License](#license)

## Installation

1. To get started, clone the repository or download the zip file.
2. Install the dependencies by running the following command in the terminal:

```
npm install
```

3. Create a .env file in the root directory and add the following environment variables:

```
NEXT_PUBLIC_GRAFBASE_API_URL
NEXT_PUBLIC_GRAFBASE_API_KEY
GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET
NEXTAUTH_URL
CLOUDINARY_NAME
CLOUDINARY_KEY
CLOUDINARY_SECRET
```

5. Create a .env file in the grafbase directory and add the following environment variables:

```
NEXTAUTH_SECRET
```

6. Run the development server by running the following command in the terminal:

```
npm run dev
```

7. Open [http://localhost:3000](http://localhost:3000) with your browser to see the project.

⭐ Note: The project may require some additional configuration to run properly. Please refer to the youtube tutorial for more information.

## Features

This project includes the following features:

- User registration and authentication using Next Auth
- Project upload with images, titles, and descriptions
- Developer profile pages with project portfolios
- Project category sorting and filtering
- GraphQL-powered data retrieval for efficient querying
- Responsive and visually appealing UI using Tailwind CSS and HeadlessUI

## Screenshots

## Technologies Used

- [Next.js](https://nextjs.org/)
- [NextAuth.js](https://next-auth.js.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [JWT (JSON Web Tokens)](https://jwt.io/)
- [GraphQL](https://graphql.org/)
- [Grafbase](https://www.graphbase.io/)
- [Cloudinary](https://cloudinary.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [HeadlessUI](https://headlessui.dev/)
- [Vercel](https://vercel.com/)

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Links

- [Link to deployed application](https://dribble-clone-nextjs13-yt-jsm.vercel.app/)

- [Link to GitHub repository](https://github.com/kt946/dribble-clone-nextjs13-yt-jsm)

- [Link to original GitHub repository by JavaScript Mastery](https://github.com/adrianhajdin/project_nextjs13_flexibble)

- [Link to youtube tutorial by JavaScript Mastery](https://www.youtube.com/watch?v=986hztrfaSQ)

## License

This project is licensed under the MIT License.

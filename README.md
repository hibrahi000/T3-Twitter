<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">T3-Twitter Application</h3>

  <p align="center">
    An awesome T3 practice project to clone twitter basic functionality and design
    <br />
    <a href="https://github.com/hibrahi000/T3-Twitter"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://t3-twitter-liard.vercel.app/">View Demo</a>
    ·
    <a href="https://github.com/hibrahi000/T3-Twitter/issues">Report Bug</a>
    ·
    <a href="https://github.com/hibrahi000/T3-Twitter/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

I have a habit of trying to learn new and fascinating ways to create new websites and applications. This is one where I am practicing this habit with the T3 Stack in making a mock twitter.

_Functionality:_

- Login using OAuth via discord
- Utilize infinite scrolling
- Add Tweets
- Like Tweets
- Follow users
- Unfollow users

Of course, there is always room for improvement and this readMe will be updated to reflect that!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![TypeScriptLogo][TypeScriptLogo]][typescript-url]
- [![Tailwindcss][Tailwindcss]][tailwind-url]
- [![tRPCLogo][tRPCLogo]][trpc-url]
- [![PrismaLogo][PrismaLogo]][prisma-url]
- [![Next][Next.js]][Next-url]
- [![**React**][React.js]][React-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

- First clone this repo and run `npm install`
- Second make sure you have an account with prisma pascale, and discord ( the developer version ).
- Third follow installation instructions
- Finally run `npm run dev`

### Prerequisites

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/hibrahi000/T3-Twitter.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Create and enter your Environment Variables in `env.js` at the root directory

- DATABASE_URL - you get this from your pascal database settings
- NEXTAUTH_SECRET - you can generate this by running : `openssl rand -base64 32` in your terminal
- NEXTAUTH_URL - for dev it will be "http://localhost:3000"
- DISCORD_CLIENT_ID - you can get this from your developer settings on discord
- DISCORD_CLIENT_SECRET - you can get this from your developer settings on discord

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Hashmat Ibrahimi
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Gmail][gmail-shield]][gmail-url]
[![Github][github-shield]][github-url]

Project Link: [https://github.com/hibrahi000/T3-Twitter](https://github.com/hibrahi000/T3-Twitter)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/hibrahi000/T3-Twitter.svg?style=for-the-badge
[contributors-url]: https://github.com/hibrahi000/T3-Twitter/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hibrahi000/T3-Twitter.svg?style=for-the-badge
[forks-url]: https://github.com/hibrahi000/T3-Twitter/network/members
[stars-shield]: https://img.shields.io/github/stars/hibrahi000/T3-Twitter.svg?style=for-the-badge
[stars-url]: https://github.com/hibrahi000/T3-Twitter/stargazers
[issues-shield]: https://img.shields.io/github/issues/hibrahi000/T3-Twitter.svg?style=for-the-badge
[issues-url]: https://github.com/hibrahi000/T3-Twitter/issues
[license-shield]: https://img.shields.io/github/license/hibrahi000/T3-Twitter.svg?style=for-the-badge
[license-url]: https://github.com/hibrahi000/T3-Twitter/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0A66C2.svg?style=for-the-badge&logo=LinkedIn&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/hashmat-ibrahimi/
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[tailwind-url]: https://tailwindcss.com/
[Tailwindcss]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[trpcLogo]: https://img.shields.io/badge/tRPC-2596BE.svg?style=for-the-badge&logo=tRPC&logoColor=white
[trpc-url]: https://trpc.io/
[PrismaLogo]: https://img.shields.io/badge/Prisma-2D3748.svg?style=for-the-badge&logo=Prisma&logoColor=white
[Prisma-url]: https://www.prisma.io/
[TypeScriptLogo]: https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white
[typescript-url]: https://www.typescriptlang.org/
[gmail-url]: mailto:hashmat.ibrahimi.21@gmail.com
[gmail-shield]: https://img.shields.io/badge/Gmail-EA4335.svg?style=for-the-badge&logo=Gmail&logoColor=white
[github-url]: https://github.com/hibrahi000
[github-shield]: https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white

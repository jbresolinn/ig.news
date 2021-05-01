<img alt="github-explorer-header" title="github-explorer" src=".docs/header.svg" />
<h1 align="center">Jamstack structure with Next.JS</h1>

<p align="center">
  <img alt="languages count" src="https://img.shields.io/github/languages/count/jbresolinn/ig.news?color=61DCFB"/>
  <img alt="repo size" src="https://img.shields.io/github/repo-size/jbresolinn/ig.news?color=61DCFB">
  <img alt="stars" src="https://img.shields.io/github/stars/jbresolinn/ig.news?color=61DCFB">
</p>

<p align="center">
  <a href="#-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies-used">Technologies Used</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>&nbsp;&nbsp;&nbsp;
</p>
<br>


## <img src=".docs/label.svg" width="18px">&nbsp; About

Ig.news is a basic structure of a blog with post preview control for people with enrollment using serverless functions and integration with third-party API's and database recording.

**Prototype:** [Click here](https://www.figma.com/file/gl0fHkQgvaUfXNjuwGtDDs/ig.news).


## <img src=".docs/label.svg" width="18px">&nbsp; Technologies used

- [Next.JS](https://nextjs.org/): Framework React <br>
- [Stripe](https://stripe.com/br):  Payment infrastructure for the internet<br>
- [FaunaDB](https://fauna.com/): Database for modern applications <br>
- [Prismic](https://prismic.io/): Content management system <br>



## <img src=".docs/label.svg" width="18px">&nbsp; Run project

```bash
# Clone this repository
$ git clone https://github.com/jbresolinn/ig.news

# Access folder
$ cd ignews

# Install dependencies with yarn or npm
$ npm install
$ yarn

# Run the project with yarn or npm
$ yarn dev
$ npx run dev

# The server will initialize in the <http://localhost:3000>
```

**OBS:** After cloning the project, create a ```.env.local``` file at the root of the project with the following structure:

```txt
# stripe
STRIPE_API_KEY=
STRIPE_SUCCESS_URL=
STRIPE_CANCEL_URL=
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=
STRIPE_WEBHOOK_SECRET=

# github
GITHUB_ID=
GITHUB_SECRET=

#faunadb
FAUNA_DB_KEY=

#prismic
PRISMIC_ACCESS_TOKEN=
PRISMIC_ENDPOINT=

```
---

Made with ❤ by Julia Bresolin! <br>
[Follow me on social networks!](https://linktr.ee/juliabresolin)
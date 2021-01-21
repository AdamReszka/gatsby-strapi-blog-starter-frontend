

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Responsive design using UIkit
- SEO and social media friendly

Pages:

- "/" to display every articles
- "/article/:id" to display one article
- "/category/:id" display articles depending on the category

### Backend

```
yarn create strapi-app backend --template https://github.com/AdamReszka/gatsby-strapi-blog-starter-backend
npx create-strapi-app backend --template https://github.com/AdamReszka/gatsby-strapi-blog-starter-backend
```

### Frontend

```bash
cd frontend
```

```bash
npm install
npm run develop
```

Optional change the default environment variables, create a `.env` file like this:

```sh
cp .env.example .env
```

Gatsby server => [http://localhost:3000](http://localhost:3000)

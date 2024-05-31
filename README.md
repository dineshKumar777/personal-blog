<p align="center">Personal blog to share my learning, thoughts and experience.</p>
<br/>

[base-template repo](https://github.com/schardev/nextjs-contentlayer-blog)

## Getting Started with base template

1. Clone the starter template:

```bash
git clone https://github.com/schardev/nextjs-contentlayer-blog
```

2. Add site information and relevant data to `lib/siteConfig.ts`.
3. Add your blog posts to `content/blog` directory with proper front-matter (see available fields [here](https://github.com/schardev/nextjs-contentlayer-blog/blob/main/schema/contentlayer/blog-post.ts))
4. Build your blog with:

```bash
pnpm build
```

5. Deploy to your hosting provider 🎉

Starting a development server isn't different either, just run:

```bash
pnpm dev
```

Now open `http://localhost:3000` to view changes to your blog as it happens.

## Directory and File Structure

| Directory/File           | Notes                                                                                                           |
| ------------------------ | --------------------------------------------------------------------------------------------------------------- |
| `app/`                   | Defines your site/blog's routes                                                                                 |
| `components/`            | All react component code lives here                                                                             |
| `content/`               | Directory where your MDX or Markdown file lives                                                                 |
| `public/`                | Static assets goes here (e.g., put all your images inside `public/images` and fonts inside `public/fonts` etc)  |
| `styles/`                | Find all styling files here                                                                                     |
| `schema/`                | Contains schema-related files                                                                                   |
| `contentlayer.config.ts` | [Contentlayer](https://www.contentlayer.dev/) configuration file (you can change your `content` directory here) |
| `lib/siteConfig.ts`      | Holds config related to the site itself                                                                         |

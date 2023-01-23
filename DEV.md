# Develop NextJS Starter Blog

```bash
yarn create next-app --experimental-app nextjs-starter-blog
```

## Setup tailwindcss

```bash
yarn add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Setup typescript alias path
```bash
# tsconfig.json
{
    "compilerOptions": {
        # ...,
        "baseUrl": ".",
        "paths": {
        "@/app/*": ["app/*"]
        }
    }
}
```
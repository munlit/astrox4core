# astrox4base &middot; Astro.build [4.4.0]
### **Tailwind - Typescript - font Inter**

## Init

- Instalamos framework [ver 4.*]

- Opciones de instalacion elegidas

  * Directory astrox4base
  * Typescript strict
  * with Template
  * with Dependencies
  * with Git

````
pnpm create astro@latest
````
````
cd astrox4base
git add .
git commit -m "Init"
````

## Dependencias

- Requerimos Tailwind
````
pnpm astro add tailwind
*pnpm dlx astro add tailwind*
````

- Generamos archivo de configuracion tailwind.config.mjs
````
pnpm add @astrojs/tailwind tailwindcss
*pnpm add @astrojs/tailwind@^5.1.0 tailwindcss@^3.4.1*

*pnpm dlx tailwindcss init*
````

- Generamos archivo de configuracion react
````
pnpm astro add react
pnpm dlx astro add react

pnpm add @astrojs/react@^3.0.10 @types/react@^18.2.56 @types/react-dom@^18.2.19 react@^18.2.0 react-dom@^18.2.0
````

- Dependencias de base
````
pnpm add @astrojs/mdx @astrojs/sitemap @fontsource-variable/inter @tailwindcss/typography @typescript-eslint/parser astro-navbar astro-seo eslint eslint-plugin-astro eslint-plugin-jsx-a11y prettier prettier-plugin-astro sass sharp tailwindcss
````
````
pnpm add @astrojs/mdx @astrojs/sitemap sharp
````
````
pnpm add @tailwindcss/typography
````
````
pnpm add @fontsource-variable/inter
````
````
pnpm add @typescript-eslint/parser
````
````
pnpm add astro-navbar astro-seo
````
````
pnpm add eslint-plugin-astro eslint
````
````
pnpm add eslint-plugin-jsx-a11y
````
````
pnpm add prettier-plugin-astro prettier
````
````
pnpm add tailwindcss sass
````
````
git add .
git commit -m "Dependencias"
````

## Estructura

- Creamos las carpetas
- Estructuramos los archivos

  * Containers
  * Components/Footer
  * Components/Header

````
git add .
git commit -m "Estructura"
````

## GitHub

- Vinculamos con github
- Push repositorio

  * Containers
  * Components/Footer
  * Components/Header

````
git remote add origin https://github.com/munlit/astrox4core.git
git commit -m "GitHub"
````

## Funcional

- Generamos extenciones de los archivos(.astro)
- Modificamos archivos
- Correjimos hasta tener una landing funcional

````
git commit -m "Funcional"
````

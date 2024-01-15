# tailwindCss

## Tailwind css setup

https://tailwindcss.com/docs/installation

### Using CDN
  <script src="https://cdn.tailwindcss.com"></script>

### Using PostCSS
step 1 : Install Tailwind CSS

NOTE: Before Install Need to have Node JS

```php
npm install -D tailwindcss postcss autoprefixer
npm install vite 
`````
Add Below code in package.json to run vite on npm start 

```php
  "scripts": {
    "start": "vite"
  },
`````
Now run above command to initialize tailwind css
```php
npx tailwindcss init
````
Now add ```` "*",```` in tailwind.config.js inside content array, Which defines we want to use tailwind css in all content.

# Installation
// - composer install
- php artisan storage:link
  <br>(dev: debugbar from github, telescope from laravel)
- php artisan migrate
- copy template to the project
- npm install
- npm -D tailwindcss
- copy tailwind.config.js to project root
- install required plugins with npm install @...
- change path in content section to "./resources/views/*.blade.php"
- create file in root postcss.config.js and copy there: export default {
  plugins: {
  tailwindcss: {},
  autoprefixer: {},
  },
  };
- add: import './main'; to app.js
- npm install sass
- insert @vite([..]) to head tag in welcome.blade.php
- npm install autoprefixer postcss
- 

# Deploy

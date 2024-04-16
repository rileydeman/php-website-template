# PHP website folder structure/template

<hr>

The PHP website folder template that rileydeman uses in his web projects!


## Using this folder template

Using of this folder structure/template is completely free of charge.
You are allowed to fork this repository and edit all the files in this template

## Important

- The homepage is not in the `index.php`, the index.php file gets automaticly the `public/home.php` file.
- The public folder is for everything that the user sees, like all the pages, images etc.
- The app folder is for everything that is back and, and what the user doesn't see, like adding items to a cart, etc.
- Be sure that the folder where the `index.php` is located, is the root from your xampp, wampp, lampp or mampp software for your localhost.
- The `public/home.php` file has the template for a web page, including the header and footer include
- The header and footer are in the `public/core folder`
- The 404 page will automaticly shown at not valid urls on your localhost or website, editing the 404 page is possible in the `public/core/errors/404.php` file

## .htacess

Mostly the `.htacces` file can't get the good file, in that case go to the `.htaccess file` and add the following code to the file:
`RewriteRule ^requestName public/requestName.php`

## Styling

For the styling from the site does rileydeman use sass, you are free to delete the sass file and folder, but in case you want to use sass be sure that you do this:

- Be sure that you have installed sass to your system, go to your global terminal and use this `npm install -g sass`
- To compile sass you need to be sure that your terminal is in the assets folder and use the following command (everytime you start working on your site) in de terminal: `sass --watch --no-source-map sass/input.sass css/output.css`
- Be sure that you connect the `.css` files to your web pages, web browsers **can't** read `.sass` and/or `.scss` files.

<hr>

More information soon!

© rileydeman
# laravel-mix-php
PHP Function for not @laravel project

# Use in Project
Add mix() to your page:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Laravel</title>

        <link rel="stylesheet" href="{{ mix('css/app.css') }}">
    </head>
    <body>
        <div id="app">
            <example-component></example-component>
        </div>

        <script src="{{ mix('js/app.js') }}"></script>
    </body>
</html>
```

And reload the page in your browser

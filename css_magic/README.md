## CSS [ Cascading Style Sheets ]

### There are 3 ways to implement css 

<ol>
    <li> InLine </li>
    <li> Internal </li>
    <li> External </li>
</ol>

## Demos 

### Inline 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>❤️ profile 🙈</title>
</head>
<!-- below given way -->
<body style="background-color: #ccdbdd;">
    <h1> Hello world </h1>
</body>
</html>
```

### INTERNAL 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>❤️ profile 🙈</title>
    <style>
        body {
            background-color: #ccdbdd;
        }
    </style>
</head>
<!-- below given way -->
<body>
    <h1> Hello world </h1>
    </body>
</html>
```

### External 

```
style.css
====
body {
    background-color: #ccdbdd;
}

hr {

    border-style: none;
    border-top-style: dotted;
    border-width: 5px;
    border-color: rgb(210, 204, 204);
    width: 10%;
    height: 0px;
}


==== Index.html 


<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>❤️ profile 🙈</title>
    <link rel="stylesheet" href="css/style.css">
</head>
```


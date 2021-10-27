# ecss

Basic CSS for simple websites.

Example:
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>0aoq/ecss</title>

    <link rel="stylesheet" href="./ecss/app.e.css">
</head>

<body>
    <app class="grid grid-place-center">
        <!-- <ecss> element = whitespace for flex/grid -->
        <ecss class="container-xl pad-full-1_2">
            <h1>Lorem, ipsum dolor.</h1>
            <h3 class="mb-2em">Lorem, ipsum.</h3>
        </ecss>

        <ecss class="pad-full-1_2 container-xl flex flex-undo flex-just-between bg-3 rad-_8em">
            <ecss class="grid grid-place-center"><text class="fs-1_875 fw-700">Lorem, ipsum.</text></ecss>
            <ecss class="grid grid-place-center">
                <p style="margin-bottom: 0;">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
            </ecss>
            <ecss class="grid grid-place-center"><a href="#" class="button flex-just-self-left pad-center-2_5 btn-shadow">Get Started</a></ecss>
        </ecss>

        <input type="text" placeholder="input">
        <textarea name="" placeholder="textarea"></textarea>
    </app>
</body>

</html>
```
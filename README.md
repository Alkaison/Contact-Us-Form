# Contact-Us-Form

Simple contact us form made using pure HTML, CSS with gradient effect 

## Live Preview

The webpage is live with the help of GitHub pages and you can visit it here: https://alkaison.github.io/Contact-Us-Form/ 

## HTML Code 

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background: linear-gradient(to top left, skyblue, violet) no-repeat center fixed; background-size: cover;">
    <div class="container-box">
        <div class="container-text">
            <h1>Contact Us</h1>
        </div>
        <div class="container-form">
            <form name="contact_form">
                
                <input type="text" class="input-field" name="name" placeholder="Your name" title="Your Name" required><br>

                <input type="email" class="input-field" name="email" placeholder="Your Email Address" title="Your Email Address" required><br>

                <input type="tel" class="input-field" name="whatsapp-number" placeholder="Your WhatsApp Number" title="Your WhatsApp Number" maxlength="10" required><br>

                <textarea name="message"  class="input-field" rows="4" cols="30" placeholder="Your Message" title="Your Message" required></textarea><br><br>

                <input type="submit" id="btn-submit" class="input-field" name="submit" value="Send Message"><br>
                <input type="reset" id="btn-reset" class="input-field" name="reset" value="Clear All">
            </form>
        </div>
    </div>
</body>
</html>
```

## CSS Code 

```CSS
.container-box {
    padding: 0px;
    margin: 0px;
    text-align: center;
}

.input-field {
    padding: 7px;
    margin: 7px;
    border-radius: 5px;
    border: 1px solid black;
    box-shadow: 2px 2px 2px 1px black;
    width: 250px;
    max-width: 500px;
    max-height: 500px;
    background-color: rgb(204, 204, 204);
}

.input-field:hover {
    background-color: white;
}

#btn-submit:hover {
    background-color: green;
}

#btn-reset:hover  {
    background-color: red;
}
```

## Screenshot

![Contact Us Form](https://github.com/Alkaison/Contact-Us-Form/blob/main/image.png)

## Feedback

If you have any feedback, please reach out to us at [Discord](https://discord.gg/dF4PHxbHpA).

## 💛 Contributing

1. To propose a change in this document or submit a new translation you can [fork this repository](https://github.com/Alkaison/Contact-Us-Form/fork) and submit a **pull request**.

2. Questions about anything? Ask me [here](https://github.com/Alkaison/Contact-Us-Form/issues/new)!

3. If you like this project, give it a ⭐ and **share it** with friends!

4. You can connect with me on [LinkedIn](https://linkedin.com/in/alkaison).

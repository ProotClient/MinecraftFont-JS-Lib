<center><img src="./MinecraftFont-Logo.png"></img></center>

# MinecraftFont JavaScript Library

MinecraftFont is a versatile and easy-to-use JavaScript library that allows developers to replicate the font used in the popular video game [Minecraft (Wikipedia)](https://en.wikipedia.org/wiki/Minecraft). This library is built to be lightweight and easy to implement, making it a great option for anyone looking to add a touch of Minecraft-inspired design to their website or web application.

Not only is it easy to use, but it also offers a wide range of customization options. Developers can choose to use the font in a variety of sizes and styles, making it perfect for both small text and large headlines. Additionally, it can be applied to different elements such as text, headings, labels, and more.

# Usage

To use MinecraftFont in your HTML Document you will need to import the Library first. This is done by pasting the following code in your `<head>` Element:

```html
<script src="https://prootclient.github.io/librarys/minecraftfont.v1_0.js"></script>
```

Now create a `<text>` Element in your Document, with any ID you want (make sure it is below the importing element):

```html
<text id="minecraftfont-element"></text>
```

Below that create a `<script>` Element like this:

```html
<script>
    minecraftFont(
        "Element ID",
        // Insert JSON Text Here; Recommended Website: https://minecraft.tools/en/json_text.php
    )
</script>
```


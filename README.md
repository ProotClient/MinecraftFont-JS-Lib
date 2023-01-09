# MinecraftFont JavaScript Library

MinecraftFont is a simple JavaScript Library that makes the font appear like in the video game [Minecraft (Wikipedia)](https://en.wikipedia.org/wiki/Minecraft).

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


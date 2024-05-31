## CSS (Cascading Style Sheets)

CSS is used to style and layout web pages. It can be applied in three ways: external, internal, and inline.

### External CSS

External CSS is defined in a separate file (e.g., `style.css`) and linked to the HTML document using the `<link>` tag inside the `<head>` section.

```html
<link rel="stylesheet" href="./style.css" />
```

### Internal CSS

Internal CSS is defined within a `<style>` tag inside the `<head>` section of the HTML document.

```html
<style>
    h1 {
        color: blue;
    }
</style>
```

### Inline CSS

Inline CSS is applied directly to HTML elements using the `style` attribute.

```html
<h1 style="color:red;">Hello</h1>
```

## HTML Elements

### Dropdown (Select) Element

The `<select>` element creates a dropdown menu. Each option within the dropdown is defined using the `<option>` tag.

```html
<select>
    <option value="inr">India</option>
    <option value="as">AS</option>
    <option>US</option>
    <option>UK</option>
</select>
```

### Audio and Video Elements

HTML5 provides `<audio>` and `<video>` elements for embedding media files.

#### Audio

```html
<audio src="audio.mp3" controls></audio>
```

- `src`: Specifies the path to the audio file.
- `controls`: Adds playback controls.

#### Video

```html
<video src="./video.mp4" controls autoplay loop></video>
```

- `src`: Specifies the path to the video file.
- `controls`: Adds playback controls.
- `autoplay`: Automatically starts playing the video.
- `loop`: Replays the video after it ends.

### Iframe Element

The `<iframe>` element is used to embed another HTML page within the current page.

```html
<iframe src="https://www.openstreetmap.org/export/embed.html?bbox=-0.004017949104309083%2C51.47612752641776%2C0.00030577182769775396%2C51.478569861898606&layer=mapnik" height="100%" width="100%"></iframe>
```

- `src`: Specifies the URL of the page to embed.
- `height` and `width`: Set the dimensions of the iframe.
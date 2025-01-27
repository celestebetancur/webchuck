# WebChucK IDE

A web-based integrated development environment (IDE) for real-time sound synthesis and music creation with ChucK!

Try it here: [https://chuck.stanford.edu/webchuck/](https://chuck.stanford.edu/webchuck/)

## What is WebChucK?

WebChucK enables Chuck to run on the web. Using WebAssembly and the Web Audio API, you can use WebChucK to build your own browser-based audiovisual projects or web apps. To learn more about WebChucK and what it can do, check out the following tutorials: [https://chuck.stanford.edu/webchuck/tutorial](https://chuck.stanford.edu/webchuck/tutorial)

*How much web could a WebChucK ChucK if we **all** could ChucK on the web?*

### Creating your own WebChucK project

If you'd like to embed WebChucK into your own site, there are two ways you can do this:

1. Link WebChucK in the `<body>` in your index.html

```html
<!-- Connect ChucK to Web Audio API, connect webchuck.js and webchuck.wasm -->
<script> var whereIsChuck = "https://cdn.jsdelivr.net/gh/ccrma/webchuck/src"; </script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/ccrma/webchuck/src/webchuck_host.js"></script>
```

2. Copy the files from WebChucK [src](./src/):

- `webchuck_host.js`
- `webchuck.js`
- `webchuck.wasm`

## WebChucK IDE Features

- Monitor runtime of ChucK's virtual machine

- Cross platform development for ChucK (mobile, iPad)

- Audio Visualizer

- Auto-generated GUI

- Access to ChucK's example library

- Vim keybindings

- Dark mode

- Precompilers (to play with possible new worlds)

### WebChucK IDE Usage

Open `index.html` with a live server, Python http.server or the like


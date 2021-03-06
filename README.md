# Simple Audio Web  Player

Simple player for your site

![Look](look.png)

## Version

**0.7.0** . Recommended for reference only. Stay tuned

## Getting Started

### Installing

```
npm installl simple-audio-web-player (not yet available)
```

### Using

#### Description of using

The wrapper function takes two arguments: a collection of elements that will become players, and a playlist as an array of objects

#### Browser

```html
<html>
    <head>
        <script src="./player.js"></script>
    </head>
    <body>
        <div class="container"></div>
        <script>
            const playlist = [
                {
                    name: 'We are the champions',
                    source: './audio/audio1.mp3'
                },
                {
                    name: 'I Want To Break Free',
                    source: './audio/audio2.mp3'
                }
            ];

            Player (
                document.getElementsByClassName('container'),
                playlist
            )
        </script>
    </body>
</html>
```

#### NodeJS

```js
const Player = require('simple-audio-web-player');

const playlist = [
    {
        name: 'We Are The Champions',
        source: '../assets/audio/audio1.mp3'
    },
    {
        name: 'I Want To Break Free',
        source: '../assets/audio/audio2.mp3'
    }
];

Player (
    document.getElementsByClassName('container'),
    playlist
)
```

## Decription

This script (44.2 kb) will generate an audio player on your web page. The package includes icons and css.

The player can switch tracks, play them separately or in a circle.

**Hotkeys**

"Space": switch track playback.

"F": switch track forward.

"B": switch the track back.

"L": switch the playback in a circle.



**Internet explorer 11 is unsupported**

Icons taken from the site https://remixicon.com/.

The font is an open font from https://fonts.google.com/.

## Error or wish?

Write to me in the mail orlov.dmitriy2303@outlook.com

## Author

Dmitry Orlov, student and novice web developer

## License

This project is licensed under the MIT License
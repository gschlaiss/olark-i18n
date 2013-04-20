# Olark Translations

Olark gives you the possibility to translate their widget in any language you want. How about we all contribute together and share our local files?

## Usage

Simply includes the  locale `.js` file you want right after where you initiate the Olark widget.

Here is an example in `HAML`, the erb `shared/chat` file contains the olark code :

```
= erb(:'shared/chat')
- if locale == 'en'
  %script{ src: '/javascripts/olark-en.js' }
- elsif locale == 'fr'
  %script{ src: '/javascripts/olark-fr.js' }
```

The usage should be similar in any other languages, feel free to send a pull request for more usage exemple.

## License

All files are licensed under a [MIT License](http://en.wikipedia.org/wiki/MIT_License), so feel free to use them as you want.
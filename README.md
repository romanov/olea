# MonoBrowser Core
MonoBrowser Core is a markdown rendering engine written in F# for MonoGame, and adaptable to desktop, mobile, and embedded applications.

## Documenation
1. Add component to your game or project

```
var olea = new OleaComponent(this)
{
    EnableDebug = true,
    EnableScrollbar = true
};

Components.Add(olea);
```

2. Open remote markdown document with `olea.Navigate("https://yoursite/readme.md")`
3. Close window with `olea.Close()` 



## Support
F#
C#

## Future
Image support

## HTML Support
Basic support of DIV, P, H1, H2, H3, HREF (block, no styles)

## Licenses
[Apos Input](https://github.com/Apostolique/Apos.Input)

[Inter font](https://openfontlicense.org/)

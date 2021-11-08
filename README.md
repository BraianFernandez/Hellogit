# Cabeceras:

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines:
Underline 1
-------------

Underline 2
============

# Formato de enfasis:
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold** o __strong__ 
- formato ~~tachado~~.
- aqui podemos usar *formato italico*, pero tambien __bold__ o el mismo ~~tachado~~.

# Listas:

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links:
- <a href ="http://www.google.com"> Esto es un link en HTML</a>
- [Esto es un link al index](index.html)

# Imagenes
![logo Github](https://e7.pngegg.com/pngimages/914/758/png-clipart-github-social-media-computer-icons-logo-android-github-logo-computer-wallpaper.png)

# Code Snippes:
- Codigo en JSON
``` JSON [
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
- Codigo en JAVA
``` 
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
```
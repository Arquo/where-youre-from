# ayoshi

Source for https://ayoshi.app, a collection of small browser games hosted on GitHub Pages.

## Layout

```
CNAME                  keeps ayoshi.app connected (don't delete)
index.html             homepage that lists every game
404.html               shown for addresses that don't exist
whereareyoufrom/       ayoshi.app/whereareyoufrom
  index.html
```

Each game lives in its own folder, and the folder name is its address: `ayoshi.app/<folder>/`.

## Adding a game

1. Create a folder with a short lowercase name, for example `mygame/`, and put the game in `mygame/index.html`.
2. In the root `index.html`, copy one `<li class="game">` block, put it at the top of the list, and change the link (`/mygame/`), the number, the art, the title, the description and the tags.
3. Update the count in `<span class="count">`.
4. Commit and push to `main`. The site updates in about a minute.

# For Kittu

A little interactive birthday story in five chapters: open an envelope, make a wish over the cake, catch butterflies to unlock a gift, discover a sweet reveal, and read a letter.

## Run locally

This is a static site with no build step. Open `index.html` in a browser, or serve the folder with:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Personalize

The message, signature, WhatsApp destination, and reply text live in the `CONFIG` block near the top of the script in `index.html`. The WhatsApp number is stored in international format without a leading `+` for the `wa.me` link. The name is also used in a few visible headings. `og-image.svg` is the editable social preview artwork; `og-image.jpg` is the image used by link previews.

## Credits

Adapted from [Lasya](https://github.com/gireeshkumarreddy/Lasya), with the recipient name and social preview personalized for Kittu.

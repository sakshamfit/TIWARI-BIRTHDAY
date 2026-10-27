# Kittu ke liye

Ek chhota sa interactive birthday story paanch chapters mein: envelope kholo, cake par wish karo, butterflies pakdo gift unlock karo, ek sweet reveal dekho, aur ek letter padho.

## Apne computer par chalao

Ye ek static site hai, koi build step nahi hai. Browser mein `index.html` kholo, ya folder isse serve karo:

```sh
python3 -m http.server 8000
```

Phir <http://localhost:8000> par jao.

## Apnaayo

Message, signature, WhatsApp destination, aur reply text sab `index.html` ke script ke upar wale `CONFIG` block mein hain. WhatsApp number international format mein hai bina `+` ke, `wa.me` link ke liye. Name kuch visible headings mein bhi use hua hai. `og-image.svg` editable social preview artwork hai; `og-image.jpg` link previews mein use hota hai.

## Credits

Adapted from [Lasya](https://github.com/gireeshkumarreddy/Lasya), recipient name aur social preview Kittu ke liye personalize kiya gaya hai.

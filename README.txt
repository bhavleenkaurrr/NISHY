# nishy birthday website

a small interactive birthday website for github pages.

## files

- `index.html` - the complete website
- `assets/nishy-childhood.png` - supplied childhood photo
- `assets/pink-gold-disco-ball.png` - supplied disco ball
- `README.txt` - this file

## github pages

1. create a new github repository.
2. upload `index.html` and the `assets` folder to the repository root.
3. go to **settings → pages**.
4. under **build and deployment**, choose **deploy from a branch**.
5. select your main branch and `/ (root)`.
6. save and wait for github pages to publish the site.

the website uses relative asset paths, so it works directly from the repository root on github pages.

## interactions

- the `reveal the gift` button runs away when the cursor approaches it.
- the `okay, i'll click here` button opens the prank page.
- the prank page automatically transitions to the final message after 45 seconds.

## editing

all visible wording is in `index.html`.
the final message can be edited in the `page3` section.
the 45-second delay is controlled by `45000` in the javascript near the bottom of `index.html`.

the site is designed to work without a build step. just upload the files to github pages.

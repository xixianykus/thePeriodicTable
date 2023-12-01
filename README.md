# the-periodic-table
CSS version of the Periodic Table of Elements


Changes to make:
* better background texture
* better gradient overlay
* a bit lighter overall
* texture for table cells

## The look

Changing the look might encourage further development.

## Hugo?

If I made this into a Hugo site I could store the data in a data file, range through and output the code for each.

Probably need one file or one object per line of the PT. TD's are given a class of blank when there is no element.

### What I'd Like

Click on an element and a whole page comes from above or the sides or somewhere with lots of info about that element.

This could be done with full page div tags that are out of view. Each tag numbered 1 to 118

#### Info:

An image?

1. number
2. weight
3. name
4. short code
5. discovered (year)
6. by who?
7. qualities and general info
8. Radio-active y/n
9. poisonous y/n


### Font scaling

Firefox imposes a minimum font size of 9px which prevents scaling of the small .elementname text.

Solutions:
1. leave it - it's not the end of the world.
2. Use a hack using the font-size-adjust bug - https://stackoverflow.com/questions/2421056/how-can-i-override-the-minimum-font-size-in-firefox


[![Netlify Status](https://api.netlify.com/api/v1/badges/cac35247-9d9f-44c4-aeea-9e8848aee5e9/deploy-status)](https://app.netlify.com/sites/the-periodic-table/deploys)
# trademindx.github.io

Public Homepage - https://trademindx.github.io

Based on a modified Creative bootstrap theme by Blackrock Digital LLC.

# running locally:
jekyll build
jekyll serve

# image optimization

convert logo.png -strip logo.png
convert header.jpg -sampling-factor 4:2:0 -strip -quality 85 -interlace JPEG -colorspace sRGB header.jpg

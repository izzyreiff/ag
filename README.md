# Anna Greenleaf photography website
A photography portfolio Jekyll website hosted on Github pages, forked from Ramswaroop.

Currently connected to Cloud9, pushed from there for simple photo consolidation and changing.

## Instructions to add images
1. Go into Cloud9 IDE, download `/images/fulls` and `/images/thumbs`
2. Add new images to `/images/fulls` folder, delete any you don't want from there
3. Upload new `/images/fulls` folder to `/images/fulls` in Cloud9, so that it is saved there **BEFORE PROCEDING**
4. Use Automator workflow [resize for ag] on computer to *crop images to dimensions* (scale to short side before crop) width: 512 length: empty 
5. Upload your resized pictures to `images/thumbs` directory.
6. Go to Cloud9 and open the terminal
7. `git add .` in the terminal
8. `git commit -a -m "updated images"` in terminal
9. `git push -u origin master` to push to github master branch
10. You're done!!
11. If you're doing a LOT of images, you should push in batches so that the Cloud9 CPU doesn't get too overwhelmed

## Custom URL
1. CNAME file 
2. DNS settings
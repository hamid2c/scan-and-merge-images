Useful tips for resizing and merging images
===========================================

Good to know:

* Import the image as you wish in gimp. Export it to a jpeg file with desired quality (e.g. 65%)
* Resize and convert to pdf (convert bbb.jpg -resize 185% bbb.pdf)


Merge with gs:

```
gs -dNOPAUSE -sDEVICE=pdfwrite -sOUTPUTFILE=combine.pdf -dBATCH 1.pdf 2.pdf
````
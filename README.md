# Book-Framework
Repository with a Framework for writing a book using LateX (pandoc + tectonic)

Steps to compile the book:

1. install pandoc
  - winget in Windows
  - apt in Debian/Ubuntu
2. install tectonic
  - scoop in Windows
  - apt/snap in Debian/Ubuntu
3. Run:
  - pandoc -f markdown-smart --toc --epub-embed-font='fonts/*.ttf' -o ./build/book.pdf metadata.txt contents.markdown chap1.md chap2.md --pdf-engine=tectonic
  - pandoc -f markdown-smart --toc --epub-embed-font='fonts/*.ttf' -o ./build/book.docx metadata.txt contents.markdown chap1.md chap2.md

folders:
- draws: save the vectorized images for exporting
- fonts: fonts used in the book
- images: images to bee included in the content
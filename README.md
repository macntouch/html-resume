This is a small HTML/CSS "framework" that I use for my resume ([cv.sample.pdf](https://github.com/buu700/html-resume/blob/master/cv.sample.pdf?raw=true)).

The CSS could use some love, as I've just been slapping on new rules when necessary; feel free to send a pull request if you ever add something to it for your own resume or do a bit of housecleaning (provided that it doesn't break/change anything in my resume, of course).

---

**Usage:** `./cv.sh input.html output.pdf "Your Name"`

As a starting point, I've included the file [cv.template.html](https://github.com/buu700/html-resume/blob/master/cv.template.html).

---

**Dependencies:**

* [Bash](http://en.wikipedia.org/wiki/Bash_\(Unix_shell\))  
(I'll make some time in the near future to add a batch script, but if you need to use this absolutely today then you'll need Unix or Cygwin)

* [Wkhtmltopdf](http://code.google.com/p/wkhtmltopdf/)

* [Pdftk](http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/)

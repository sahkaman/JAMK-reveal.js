# Reveal.js template for JAMK University of Applied Sciences

All the magic here happens with https://github.com/hakimel/reveal.js/

Hopefully I've respected the licence as well as possible. Please give me a comment if something is missing!

Demo of this can be found at http://student.labranet.jamk.fi/~sahka/lectures/reveal/jamk.html

## Export to PDF

You can use: https://github.com/astefanutti/decktape

Simple steps (on Ubuntu):

```
curl -L https://github.com/astefanutti/decktape/archive/v1.0.0.tar.gz | tar -xz --exclude phantomjs
cd decktape-1.0.0
curl -L https://github.com/astefanutti/decktape/releases/download/v1.0.0/phantomjs-linux-x86-64 -o phantomjs
chmod +x phantomjs
./phantomjs decktape.js reveal http://student.labranet.jamk.fi/~sahka/lectures/reveal/jamk.html jamk.pdf
```
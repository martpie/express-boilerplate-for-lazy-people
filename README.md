# express-boilerplate-for-lazy-people

A boilerplate for lazy people:

- node
- express
- jade
- stylus
- bootstrap (CDN)
- basic SEO
- gzip compression
- minify js/css
- force-domain
- forever

Feel free to contribute !

### What does "lazy people" mean ?

That means me.

Otherwise, here are some reasons why you could use this:

- You want to create a minimalistic website from scratch like, really fast, with only a few views
- Small audience (like a personal website)
- You don't want to bother about gulp, grunt and everything for your build process, you just want middlewares

### Download'n'run

- Download all that stuff
- `npm install -g forever && npm install`
- `forever start app.js`
- Browse to `http://localhost:3000`

### Stop it ?

- `forever stop app.js`

### Care about

- `www` will redirect to `non-www`, you can change that in `app.js`

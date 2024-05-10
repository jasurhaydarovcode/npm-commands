<!-- <h1 align="center"></h1> -->
<h1 align="center">
    <img src="./.github/npm.png" width="100">
</h1>

<h1 align="center">Hi, In this Repo you can use npm package codes</h1>

## You must have `NodeJs` installed for these commands to work
---

# <img align="center" src="https://raw.githubusercontent.com/jasurhaydarovcode/jasurhaydarovcode/main/FremWork%20%26%20Library/Pug-Dark.svg" alt="PUG" title="PUG" width="60"> PUG


## PUG Install NPM 
```bash
npm i pug
```

## Watch PUG File, `Converts PUG to HTML` 
```bash
pug -w ./ -o ./html -P
```

### This code is hard to remember, so I recommend adding the **`"pug": "pug -w ./ -o ./html -P"`** command between the script tag in the `package.json` file.

### Script command to shorten, in such a way
### 
```json
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "pug": "pug -w ./ -o ./html -P"
  },
```

---

# <img align="center" src="https://github.com/jasurhaydarovcode/jasurhaydarovcode/raw/main/FremWork%20&%20Library/sass.webp" alt="SASS" title="SASS" width="60"> SASS


## SASS Install NPM 
```bash
npm i sass
```

## Watch SASS File, `Converts SASS to CSS` 
```bash
sass -w sass/
```

### This code is hard to remember, so I recommend adding the **`"sass -w sass/"`** command between the script tag in the `package.json` file.

### Script command to shorten, in such a way
### 
```json
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "sass": "sass -w sass/"
  },
```

---

# <img align="center" src="https://github.com/jasurhaydarovcode/jasurhaydarovcode/raw/main/FremWork%20&%20Library/bootstrap.svg" alt="SASS" title="SASS" width="60"> BOOTSTRAP


## Bootstrap Install NPM 
#### If you simply type npm i bootstrap you will download the latest version of bootstrap
```bash
npm i bootstrap
```

### If you want to download the version of bootstrap you want, you can see in the example below, here is the code for bootstrap version 5.3.3
```bash
npm install bootstrap@5.3.3
```
# Bootstrap Icons via npm
## Using bootstrap icons using npm
```bash
npm i bootstrap-icons
```
## Binding bootstrap icons to html
```html
<link rel="stylesheet" href="/node_modules/bootstrap-icons/font/bootstrap-icons.css">
```

---

# <img align="center" src="./.github/percel.png" alt="Percel" title="PERCEL" width="60"> PERCEL


## Percel Install NPM 

### Parcel recall

```bash
npm install --save-dev parcel
```

### run
```bash
npx parcel ./index.html
```

### Watch
```bash
http://localhost:1234/
```

---
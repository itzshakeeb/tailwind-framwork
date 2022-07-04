
<p align="center">
  <h3 align="center"># Tailwind-CSS-add create by - ShAkEeB</h3>
</p>

## How to

You can download Zip or by usinging git clone -url.
If you want cerate by yourself
Follow the rules :-

1. install Node software;
2. check version :

```sh
node --version
```

3. vs code plugin - Tailwind CSS IntelliSense;
4. got to your project folder :

```sh
npm init -y
npm i -d tailwindcss
npx tailwindcss init
```

4. crate two folder - name : src , output & create - a css file tailwind.css in src folder (any other name can use)
5. into the .css file write —

```sh
@tailwind base;
@tailwind components;
@tailwind utilities;
```

6. Create .vscode/settings.json file ---
7. in settings.json -

```sh
 {
  "css.validate": false,
  "tailwindCSS.emmetCompletions": true}
```

8. Create a build script:

```sh
  "scripts": {
    "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
  },
```

```sh
npm run build
```

9. create a html file and link the ./output/tailwind.css

## If you want to download my files :
   Go there you download my file. Open with terminal or cmd
   type
```sh
git checkout master
```
   

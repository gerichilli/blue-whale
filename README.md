# blue-whale
I made this website along Jonas Schmedtmann's course on Udemy. I changed all pictures, colors, and some effects that I like.
First time, I had many problem when I installed npm, so I decide to note my process. Because Jonas use Mac, so I can't relate with my case. I searched google too much. I spent about a day when prefix. I'm using Window 10.

I. Setting

1. Download nodejs at https://nodejs.org/en/ and install it
2. On the terminal of VSCode enter:  npm install –g npm 
3. Go to Control Panel\All Control Panel Items\User Accounts to change my environment variables -> choose path -> edit -> new -> C:\Program\nodejs (or place of nodejs on your computer)
4. On the terminal of VSCode enter:  npm init (to create json file)
5. Enter name, version, description etc.
6. npm install node-sass --save-dev
7. Write compile:sass scripts in packpage.json file then enter: npm compile:sass
8. live-server

II. Setting up the build process

1. Compilation: npm run compile-sass
2. Concatenation: first install concat by entering: npm install concat --save-dev 
   Then run it: npm run concat-css
3. Prefixing: I had problem at this step, fisrt you must install autoprefixer and postcss-cli

npm install autoprefixer --save-dev

npm install postcss-cli --save-dev

npm run prefix-css

And it did not work on my computer, due to permission or something I couldn't understand

But when I enter this, my problem gone: 

npm --save install postcss-scss

npm run prefix-css

Hope that help you too!





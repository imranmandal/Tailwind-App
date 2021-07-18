<!-- All the things here are for my future refefrence ;) piece -->

<!-- Deprication Solution -->

https://github.com/tailwindlabs/tailwindcss/discussions/1889#discussioncomment-896668

<!-- Step 1 -->

Create style.css in /src folder

<!-- Step 2 -->

Put these lines in styles.css -
@tailwind base;
@tailwind component;
@tailwind utilities;

and run - npm run build-css - in the terminal

"build-css" is a cmd specified in package.json

<!-- Step 3 -->

To customize the default css of tailwind create a folder -

tailwind.config.js -

by typing in terminal-
npx tailwindcss init --full

"--full" is a flag which will create tailwindcss.config.js with default settings

Now configure the tailwindcss.config.js as needed

After all configuration don't forget to re-build @ref-line-15

<!-- step 4 -->

If we to extend the default tailwind css

we can create tailwindcss.config.js without "--full" flag

And now I can add my styles inside extend in tailwind.config.js

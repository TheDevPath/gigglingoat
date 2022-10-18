# Welcome to The GigglinGoat

Let's get giggling goat started with the meme marketplace.

Authentic meme tokens to prove your meme is legit!

1. Create a folder and name it GigglinGoat
2. Open a terminal at the GigglinGoat folder
3. Type `code .` to open the folder in VS Code
4. Create a new file named `README.md`
5. Congratulations you just created this file in the future!

> :rocket:...Onward Scryptonauts we have more time travelling to do.

Let's start out by generating a new scrypto package so that we can set up our meme token blueprints.

1. Open up the integrated terminal and run `scrypto new-package blueprints`
   > This will create a new folder named blueprints you can of course name it whatever you prefer.

> Inside this folder will be the boiler plate project to get our meme token blueprints started.

2. Open up the `blueprints/src/lib.rs` and then delete eveything.

3. Add `mod MemeToken` at the top and save

4. In the src folder create a new file named `MemeToken.rs`

> The file should be open upon creation start typing blueprint then select the blueprint snippet from the hint autocomplete popup.

5. At the first snippet tab stop name the struct & impl `MemeToken` name the rest whatever you want.

Now Let's get our source control set up.

1. In the terminal type `git init`
   > This will initialize a new local git repository that we can use to track our changes.
2. Add this read me file and commit it with the initial commit message using the VS Code git User interface.
3. Go to your github profile and create a new repository
4. Back in the terminal grab the commands like this from your newly created repo and run them in order one line at a time

```
git remote add origin git@github.com:TheDevPath/gigglingoat.git
git branch -M master
git push -u origin master
```

Refresh the page on github after the final command finishes running and you should now see your project up on github as well.

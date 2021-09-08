# CREATE REPOSITORY

    1. Head over to your github repositories and click on button `New`.
    2. Name your Repository username.github.io, where `username` is your github username.
    3. Make Repository Public, leave everything else unchecked (Unless you need you know you need them).
    5. Click `Create Repository` Button.

# CLONE TO YOUR LOCAL
### 1. Open your preferred terminal.
### 2. Go to folder where you are gonna place the project.
``` cd /path/to/destination/folder ```

``` git clone https://github.com/username/username.github.io```

``` cd username.github.io ```
##### if you have Visual Studio Code then run command below to open working folder.
``` code . ```
### Now that you have your Project set up, only thing left to do is create _index.html_ file

You can create this file any way you want, place it in root directory of the project. It Also helps if you put some default markup for testing. Here's example for it:
```html
<!DOCTYPE html>
<html>
<body>

<h2>Hello From Redberry!</h2>
<p>This is a test website for testing out github-pages, if you see this that means it's working 🎆🎆🎆</p>

</body>
</html>
```

now only thing left to do is push our new file to github and test it out, run:
```
git add index.html

git commit -m "Created Index.html page for github pages"
```

#### Now Run:
```
git push origin master 
``` 

#### OR, if your main branch is called `main`

```
git push origin main 
``` 


### That's it

Go to https://username.github.io.
If you did everything correctly until now, then you should see:

`Hello From Redberry!`
        

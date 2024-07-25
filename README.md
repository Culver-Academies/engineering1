# Applications of Engineering 1

Welcome to the website for Applications of Engineering 1 at Culver Academies.

## Website Maintenance Tips

Use GitHub desktop to sync files with your local computer.

Here are common commands for updating the website.

In the Anaconda prompt, run

```
jupyter-book build ./
```

inside the folder with the website material to locally build the website.

Next, check the local copy.

Once you are happy, in the same folder, run:

```
ghp-import -n -p -f _build/html
```

to publish the website online.

Finally, you can run:

```
jupyter-book clean ./
```

in the same folder to remove the temporary build files. This helps keep your local git folder clean.

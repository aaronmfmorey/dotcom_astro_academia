# Aaron Morey Dot Com
This site is based on the template [Astro Academia](https://github.com/maiobarbero/astro_academia).

I have made changes to it for my own purposes, particularly adding a submodule to supply the content rather than storing 
it in the main repository.

## Repository Setup
### Add submodule
```zsh
git submodule add git@github.com:your_organization/content_submodule.git
git submodule init
git submodule update --remote
```
### Link in other submodule content if needed.
```
ln -s ./content_submodule/images ./src/asssets/images
```
Then add the symlinked content folder to `.gitignore`
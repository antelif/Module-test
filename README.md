# Module-test
The sole purpose of this repo is to practice git submodule.
For the test submodule `Submodule-test` see [here](https://github.com/antelif/Submodule-test.git).

## Commands
### Add a submodule to repo
`git submodule add https://github.com/antelif/Submodule-test.git`
### Clone a project with <i>empty</i> submodules
1. `git clone https://github.com/antelif/Module-test.git`<br/>At this point you should have the `Module-test` files but non of the submodules' files yet.
2. `cd Submodule-test`
3. `git submodule init`
4. `git submodule update`<br/>At this point you have fetched the files of `Submodule-test` as well.<br/>Steps 2-4 should be repeated for each submodule you wish to fetch locally.
### Clone a project with <i>non-empty</i> submodules
1. ` git clone --recurse-submodules https://github.com/antelif/Module-test.git`
### Fetch submodules of an <i>already-cloned</i> project
1. ` git submodule update --init`

## Sources
- [7.11 Git Tools - Submodules](https://github.com/antelif/Submodule-test.git)

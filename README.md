# Configuration

## My Thanks And Appreciation 
**These personal ~/.dotfiles are mostly preprogrammed elements and are part of my home directory thanks to everyone here:** 
1. [Mark Otto](https://github.com/mdo/config)
2. [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)
3. [George Hotz](https://github.com/geohot/configuration)
4. [MikeMcQuaid/strap](https://github.com/MikeMcQuaid/strap)
5. [cowboy/dotfiles](https://github.com/cowboy/dotfiles)
6. [gf3/dotfiles](https://github.com/gf3/dotfiles)
7. [matijs/dotfiles](https://github.com/matijs/dotfiles)
8. [Kevin Suttles awesome defaults project](https://github.com/kevinSuttle/macOS-Defaults)
9. [Gregory Pakosz @gpakosz](https://github.com/gpakosz)
- vim @ [gpakosz/.vim](https://github.com/gpakosz/.vim)
- tmux @ [gpakosz/.tmux](https://github.com/gpakosz/.tmux)
10. [oh my zsh](https://github.com/ohmyzsh/ohmyzsh)

## You may want to install a new version of the dotfiles. 

### Using git and the bootstrap script 

Setup starts in git or curl (see "Using Curl" below).

#### Set Up Using Git
```bash 
git clone https://github.com/eBenNewell/configuration.git && cd configuration && source bootstrap.sh
```
#### Set Up Using Curl
```
cd; curl -#L https://github.com/eBenNewell/configuration/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,bootstrap.sh,.osx,LICENSE.txt}
```

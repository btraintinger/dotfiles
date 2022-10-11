# My dotfiles, managed by [chezmoi](https://github.com/twpayne/chezmoi).

## install

```sh
chezmoi init btraintinger --apply
```

## use of bitwarden secrets for ssh and gpg

Install the [bitwarden-cli](https://bitwarden.com/help/article/cli/).  
Then log in and unlock the vault.  

```sh
bw login <EMAIL-ADDRESS>
bw unlock
export BW_SESSION="<SESSION-ID>"
```

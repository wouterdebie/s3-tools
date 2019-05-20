# S3 tools
This repo contains a small scripts that make my life easier when working with Amazon S3

- `s3`: wrapper script for `aws-vault` that enables profile and path completion when using S3. Completion only works if you're already authenticated (i.e. run a `s3 <profile> ls` one time without touching the TAB key).
- `_s3`: zsh completion script. Put it somewhere in your `fpath` (in my case `~/.oh-my-zsh/custom/completion`)

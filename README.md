Dockerfile for [u1nd0/neovim](http://hub.docker.com/r/u1and0/neovim)

[!screen](https://github.com/u1and0/docker_neovim_env/blob/u1and0-screenshot/Screenshot%20from%202019-01-27%2014-29-20.png)

# Install & Run

```
docker pull u1and0/neovim
docker run -it --rm -v `pwd`:/work -w /work u1and0/neovim
```

# Version
v1.0.0          ditfiles version v1.13.3
v0.2.1          install vimproc
v0.2.0          [add] ctags/gtags
v0.1.1          [rm] lynx no need [add] comment versions info
v0.1.0           Neovim container v0.1.0

# Description
* Archlinux コンテナベース([u1and0/archlinux](http://hub.docker.com/r/u1and0/archlinux)
* neovimインストール済み
* <kbd><C-Z></kbd>によるsuspendは無効化してあるので、代わりにdockerのdetach<kbd>C-P</kbd><kbd>C-Q</kbd>を使う
* プラグインインストール済み(詳細は[dotfiles](https://github.com/u1and0/dotfiles/tree/master/.config/dein))

# Plugins

1. Shougo/neomru.vim
2. Shougo/neoyank.vim
3. zchee/deoplete-jedi
4. davidhalter/jedi-vim
5. lambdalisue/vim-pyenv
6. w0rp/ale
7. thinca/vim-quickrun
8. yuta-masano/hz_ja.vim
9. fatih/vim-go
10. zchee/deoplete-go
11. yuratomo/w3m.vim
12. itchyny/lightline.vim
13. maximbaz/lightline-ale
14. mgee/lightline-bufferline
15. Shougo/dein.vim
16. osyo-manga/vim-precious
17. Shougo/context_filetype.vim
18. w0ng/vim-hybrid
19. tpope/vim-fugitive
20. airblade/vim-gitgutter
21. cespare/vim-toml
22. vim-jp/vimdoc-ja
23. terryma/vim-multiple-cursors
24. t9md/vim-quickhl
25. tomtom/tcomment_vim
26. scrooloose/nerdtree
27. tpope/vim-obsession
28. tpope/vim-surround
29. tpope/vim-repeat
30. jiangmiao/auto-pairs
31. terryma/vim-expand-region
32. hynek/vim-python-pep8-indent
33. bronson/vim-trailing-whitespace
34. Yggdroot/indentLine
35. Shougo/neocomplcache
36. Shougo/neosnippet
37. Shougo/neosnippet-snippets
38. ervandew/supertab
39. majutsushi/tagbar
40. junegunn/fzf.vim
41. jszakmeister/markdown2ctags
42. lambdalisue/vim-gista
43. tpope/vim-abolish
44. tpope/vim-unimpaired
45. vim-scripts/YankRing.vim
46. alvan/vim-closetag
47. kshenoy/vim-signature
48. thinca/vim-ref
49. mojako/ref-sources.vim
50. mfumi/ref-dicts-en.git
51. tokuhirom/jsref
52. mustardamus/jqapi
53. Shougo/deoplete.nvim
54. Shougo/denite.nvim
55. Shougo/vimproc.vim
56. ozelentok/denite-gtags
57. roxma/nvim-yarp
58. roxma/vim-hug-neovim-rpc
59. Shougo/defx.nvim
60. sjl/gundo.vim
61. fedorenchik/VimCalc3
62. vim-airline/vim-airline
63. vim-airline/vim-airline-themes
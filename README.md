# nerd-fonts
source fonts: https://github.com/oswystan/code-fonts

font patcher script: https://github.com/ryanoasis/nerd-fonts/releases/latest/download/FontPatcher.zip

convert all ttf or otf to nerd fonts

```shell
$ wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/FontPatcher.zip
$ unzip FontPatcher.zip -d fontpatcher
$ sudo apt install -y fontforge
$ fontforge -script ./fontpatcher/font-patcher --complete xxx.ttf

```


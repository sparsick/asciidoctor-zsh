# .oh-my-zsh Plugin for [Asciidoctor](http://asciidoctor.org/)

## Installation

Download the plugin into the custom plugin folder of oh-my-zsh
```shell
cd $ZSH/custom/plugins
git clone https://github.com/sparsick/asciidoctor-zsh asciidoctor
```
Activate the plugin. Add `asciidoctor` to the `plugins` list in the file `.zshrc`
```shell
plugins=(git git-extras history mvn web-search asciidoctor)
```

## Usage

### Aliases

| Alias                | Command  |
|----------------------|--------------|
|adoc | asciidoctor -D target|
|adocpdf | asciidoctor -r asciidoctor-pdf -b pdf -D target|

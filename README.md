# syntastic-swiftlint.vim
Swift syntax checker with syntastic and SwiftLint

## Requirements

- [SwiftLint](https://github.com/realm/SwiftLint)
- [syntastic](https://github.com/scrooloose/syntastic)

## Install

### SwiftLint

```
brew install swiftlint
```

### syntastic and this plugin

```vim
" exsample: with NeoBundle
NeoBundle 'scrooloose/syntastic'
NeoBundle 'tokorom/syntastic-swiftlint.vim'

let g:syntastic_swift_checkers = ['swiftlint']
```

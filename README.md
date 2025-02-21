# SONiC USERS JP WEB PAGE

## Getting Started

### Install Hugo_extended

[公式サイト](https://gohugo.io/getting-started/installing/)を参考に、Hugo extendedをインストールする。  

### Install Node

ビルドに利用するため[Node.js](https://nodejs.org/ja/)をインストールする。

### Build site on local

```bash
git clone https://github.com/ntApss/sonic-users-jp.github.io.git
cd sonic-users-jp.github.io
git submodule update --init --recursive
npm install
hugo server -D -F
```



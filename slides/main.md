<!-- classes: title -->

# 地味に嬉しい設定ファイル管理テクニック

<div class="bottom">
  <h4>2019/10/24 俺得フロントエンド #2 @ OPT Technologies</h4>
  <h4 class="right">#oretoku_frontend</h4>
</div>

---

<!-- textlint-disable -->

import icon from '../images/euxn23.png';

# Who?

#### Yuta Suzuki (@euxn23)

<br />

<img src={icon} width={200} />

<br />

### Engineer @ Japan Digital Design

<!-- textlint-enable -->

---

# 設定ファイルを便利に管理する俺得ツール作った

<div class="padding" />

- #### npmignore-aggregate
- #### json-stringify-cli
- #### gist-fetch

---

# [npmignore-aggregate](https://github.com/euxn23/npmignore-aggregate)

<div class="padding" />

- #### npmignore を publish 時に .gitignore から動的生成できるようにするシンプルなツール
- #### .gitignore と .npmignore の二重管理をやめたいので
- #### ~/.gitignore で管理してる .idea とかが混じっちゃうのを防ぎたいので

---

import npmignoreAggregate from '../images/npmignore-aggregate.png';

<img src={npmignoreAggregate} width={800} />

---

## Demo

---


# [json-stringify-cli](https://github.com/euxn23/json-stringify-cli)

<div class="padding" />

- #### module.exports を json にするツール
- #### json を書くとき js で書きたいこともままあるので
- #### js -> yaml にしたいときとかままあるので

---

import jsonStringifyCli from '../images/json-stringify-cli.png';

<img src={jsonStringifyCli} width={800} />

---

## Demo

---

# [gist-fetch](https://github.com/euxn23/gist-fetch)

<div class="padding" />

- #### gist からファイルを持ってくる
- #### git で tsconfig.json とか管理するのしんどいので
- #### でも毎回何かのプロジェクトから持ってくるのはしんどいので

---

import gistFetch from '../images/gist-fetch.png';

<img src={gistFetch} width={800} />

---

## Demo

---

# ご静聴ありがとうございました

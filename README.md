## 仮想環境の起動
`finch vm start`

## 仮想環境の停止
`finch vm stop`

## run
以下はテスト
`finch run --rm public.ecr.aws/finch/hello-finch`

## コンテナ
dockerと使い方は多分同じ
`finch container {command}`

## イメージ
dockerと使い方は多分同じ
`finch image {command}`

## compose
特に何もしなくても使える。dockerと使い方は多分同じ
`finch compose {command}`

以下ならバックグラウンドで立ち上げが出来るし
`finch compose up -d`

様子みたいならいつもどおり以下で
`finch compose ps`

止めるなら以下
`finch compose stop`

止めてコンテナ消したいならいつもの
`finch compose down`
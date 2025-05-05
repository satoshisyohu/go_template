

#### ディレクトリ構成
<pre>
.
├── README.md
├── app
│   └── main.go 
└── pkg // 
     ├── adapter
     │   ├── db // db client等
     │   └── repository // repositoryの実態
     ├── code // code値等
     ├── domain // ドメイン層
     │   ├── aggregate db等から取得した値を集約する
     │   ├── model // ドメインモデル
     │   ├── repository // repositoryのinterface
     │   └── rule // ドメインルール
     │       └── impl
     ├── handler // handler層
     │   └── dto // handler層で使用するDTO
     ├── infrastructure // usecase層
     │   └── impl // usecaseの実装
     └── resource // 設定ファイル等
</pre>

## todo 
- [ ] TaskFileの作成
- 
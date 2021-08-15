HTML マークアップ間違い

\<ul>タグの直下に\<div>タグを使用するのはアンチパターン。
以下のように\<li>タグ内に\<div>タグを配置するのが正しい構造。
一旦、練習の本質には問題ないのでこのまま進める。

    <ul>
      <li>
        <div>
          <p>TODOです</p>
          <button>完了</button>
          <button>削除</button>
        </div>
      </li>
    </ul>

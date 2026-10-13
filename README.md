# Fotoshiって何？

古橋研究室 月1ハッカソン（2026年10月）で、写真で地図を更新するアプリ「Fotoshi」を実際に使ってみた体験レポートです。

🔗 **レポートページ（GitHub Pages）**：https://furuhashilab.github.io/Hackathon_Oct_RitoYamasaki/  
📝 **Medium版の記事**：https://medium.com/furuhashilab/fotoshi%E3%81%A3%E3%81%A6%E4%BD%95-2a965cd535de

## Fotoshiとは

[Fotoshi](https://fotoshi.com/) は、身の回りの場所や物を撮影し、地図と結びついた「今そこに何があるか」の記録を積み上げていく参加型の写真プラットフォームです。投稿写真はCC BY 4.0で公開され、OpenStreetMapなどのオープンな地図をより新しく、正確にするために活用されます。

## レポートの内容

- Fotoshiの特徴（Mapillaryなど他サービスとの違い）
- UI（プロフィール・カメラ・マップ）
- レイヤー変更の試行（地理院タイルの追加）
- 感想
- 気になったバグ
  - 屋内で撮影した写真が地図からすぐ消える
  - パスワード再設定のコードがGmailに届かない
  - 地図が韓国語表記になる

## ファイル構成

```
.
├── index.html   # レポートページ本体
├── README.md
└── images/      # アプリのスクリーンショット
    ├── FotoshiUI01_profile.png
    ├── FotoshiUI02_camera.png
    ├── FotoshiUI03_map.png
    ├── impression.png
    ├── bag01.png
    ├── bag01_disapper.png
    ├── bagu02_code.png
    ├── bag02_gmail.png
    ├── bag03_inkorean.png
    └── bag03_inJapanese.png
```

## 作成者

山﨑 璃音（Yamasaki Rito）／青山学院大学 古橋研究室

## ライセンス

©FuruhashiLab, CC BY 4.0  
地図タイル：[地理院タイル](https://maps.gsi.go.jp/development/ichiran.html)（国土地理院）

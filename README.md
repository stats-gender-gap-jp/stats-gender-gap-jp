### About
主に日本国内のジェンダー格差について  
様々な📊グラフで可視化するサイトです。

まずは 🏛️政治💰経済 分野を中心にしたデータを可視化していく予定です。

政府統計など、公式に公開されている資料をもとに作成していますが

🤯公式資料は数字の羅列だけで読みづらい  
😵‍💫実際にどの程度ジェンダーギャップがあるのかが分かりにくい  
🤔自分たちができることを考えるにはどうすれば？  
といった点に問題を感じてこのサイトを作成しました。

詳細は[こちら](https://stats.gender-gap.jp/about/)に記載しています。

----
### Live Production
https://stats.gender-gap.jp/

based on [hugo-coder](https://github.com/luizdepra/hugo-coder/)

----
### Data source
https://stats.gender-gap.jp/source/

データ更新時は、

- [スプレッドシート](https://docs.google.com/spreadsheets/d/1t7u3Dr85o06OIvaO49LKOipf7ot3SjRVtyXtDI0XL6E/)の該当列データを変更
- SSSAPI側をupdate
- ローカル側で `hugo server --ignoreCache` で動作確認
- ローカル側で `hugo --ignoreCache` でリビルド
- リビルドしたpublicファイルをPRに出してmerge

で反映しています。

※セキュリティの観点より、  
現状では管理人のみ作業可能にしています。  

----
### Contact

- コメント、ご意見など
- データ更新およびサイト改善等のcontributionに関するご相談

などございましたら、  
こちらの[フォーム](https://docs.google.com/forms/d/e/1FAIpQLSdv7u_pG63IgZkLBH09SmNOoJ9VfIWQhMM5j2K6denEe92D-Q/viewform) よりご連絡ください.  

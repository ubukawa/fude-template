# fude-template
法務省登記データをベクトルタイルにするためのテンプレート（ラズベリーパイを利用）

# Source
法務省により公開されている登記所備付地図データを、(一社)社会基盤情報流通推進協議会が、shapefile、geojsonに変換したデータです。
（出典）　「登記所備付地図データ」（法務省）
- 北海道根室市（サンプルとして入れています）
# Usage

```
git clone https://github.com/ubukawa/fude-template
cd fude-template #Then, plese delete sample file in 0_src and upload your file(s) in 0_src.
sh ./geojson.sh # If you uploada shape files, run shape.sh instead of geojson.sh.
```


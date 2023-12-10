# 参加プロジェクト一覧
データサイエンスやバイオデータ解析で参画してきたプロジェクトや経験技術についてまとめています。

## RNA-Seqデータを使用したメタアナリシスによる肝細胞癌における薬剤感受性糖鎖関連遺伝子シグネチャーの同定

### Collaborator
HONDA Biotech. Laboratory
### Role
データサイエンス / データ可視化 / メタ解析
### Participation period
2022年2月 - 2023年4月 （1年3ヶ月）
### Skill
R / clusterPlofiler / ggplot2
### Keyword
計算生物学 / システム生物学 / 生物統計学 / 統計データ解析 / 生物情報学 / 医療統計 / 癌研究 / 創薬 / RNA-seq / シングルセルシーケンシング / PCA / クラスタリング / 遺伝子マーカー /  肝臓病 / 
### Summary
薬剤刺激に対する糖鎖関連遺伝子プロファイルの応答についての理解はまだ不完全です。本研究では、薬剤処理された肝がん細胞に関する公開データベースからシークエンス・リード・アーカイブデータを検索し、バイオインフォマティクスのメタアナリシスを通じて糖鎖関連遺伝子の薬剤反応を包括的に分析することを目指しました。

### Method
- 解析に使用するLinux環境イメージを構築し、公共データベースより取得した86サンプルあるRNA-seqデータを処理するパイプラインコードを準備し、各発現量データを得た。
- 得られた発現量データは、主成分分析による寄与率・factor Loadingの比較、Score法によるメタ解析、フィッシャーの正確確率検定をベースにしたエンリッチメント解析など統計解析をRを用いてコーディングした。これにより各薬剤刺激における糖鎖関連遺伝子シグネチャーの取得を行った。

### Contribution
本研究を発案し、研究の構想と設計、実験の設計、公開データセットの選定、データのダウンロードと処理、データ分析スクリプトの作成、全データの解釈、全図表の作成を行い、主要な論文のテキストを執筆しました。本研究成果はglycoconjugate誌に投稿し、査読を受けている。

### Data Availability
- [Metadata of RNA-Seq Data Samples from Drug-Stimulated Liver Cancer Cells](https://figshare.com/articles/dataset/Metadata_of_RNA-Seq_Data_Samples_from_Drug-Stimulated_Liver_Cancer_Cells/23573913)
- [GlycoGenes Matrix: Drug-Induced Liver Cancer Cell RNA-seq Data of Glycogenes](https://figshare.com/articles/dataset/GlycoGenes_Matrix_Drug-Induced_Liver_Cancer_Cell_RNA-seq_Data_of_Glycogenes/23573910)
- [Whole Gene Matrix: Drug-Induced Liver Cancer Cell RNA-seq Data of All Genes](https://figshare.com/articles/dataset/Whole_Gene_Matrix_Drug-Induced_Liver_Cancer_Cell_RNA-seq_Data_of_All_Genes/23573871)

## 希少疾患患者の全ゲノムシーケンスデータの解析

### Collaborator
[クリニックフォア田町](https://www.clinicfor.life/tamachi/)
### Role
データサイエンス / データ可視化 / バイオマーカー探索 / 臨床様相理解
### Participation period
2023年10月 - 現在
### Skill
R / Python / Linux / snpshft / DEseq2 / clusterPlofiler / Cytoscape / 

### Keyword
Whole Genome Sequence（WGS） / マルチオミクス / 機械学習 / ネットワーク解析 / 次世代シーケンサー / 免疫学 / 計算生物学 / システム生物学 / 生物統計学 / 統計データ解析 / シングルセルシーケンシング / バイオマーカー探索 / RNA-seq / 遺伝子ネットワーク解析

### Summary
希少疾患患者の疾患原因は遺伝的な変異の経過をたどる場合が多く、本患者においても同様のことが言える可能性がある。WGS解析とRNA−seq解析を組み合わせたマルチオミクス解析では疾患原因の遺伝的背景を探る上で協力な手法となる。本研究では、希少疾患患者の血液検体からマルチオミクス解析によって疾患原因となっているバイオマーカーを探索する。

### Method
- 希少疾患患者から取得した全血検体からWGS・RNA−seq解析を実施。希少疾患特有のゲノム変異を探索するため得られたWGSデータに対して、バリアントコールを行い、ToMMoやclinberなどといったDBのアノテーションを付与した。
- RNA-seqデータでは、患者検体と健常者のデータに対してDEGを取得し、遺伝子発現量変動の上位のものに対して解析を行った。
- WGS解析でANNOTATION IMPACTがHIGHやMODERATEでラベリングされた変異に関して、RNA-seqデータの発現量と比較した。また、CytoscapeによるStringAppの拡張機能を用いてタンパク質相互作用遺伝子ネットワークの構築を行い、各遺伝子の中心性をスコア化した。
- RNA−seq解析によるDEG、WGS解析によるANNOTATION IMPACT、遺伝子ネットワークからの中心性スコアを用いてZ-SCOREによるスコアリングを実施した。

### Contribution
本研究の実験の設計、データのダウンロードと処理、データ分析スクリプトの作成、データの解釈、図表の作成を行い、現在も主要な論文のテキストを執筆している。

## COVID-19患者群の前向きコホート結果におけるサンプリングバイアスの有無の検討

### Collaborator
[名古屋大学医学部附属病院・救急科](https://www.med.nagoya-u.ac.jp/hospital/departments/emergency_c-m/)

### Role
データサイエンス / データ可視化 / メタ解析
### Participation period
2023年3月 - 現在

### Skill
R / Linux / Nextflow / Seurat / ggplot2 / Cell Ranger 

### Keyword
データサイエンス / データ可視化 / 計算生物学 / システム生物学 / 生物統計学 / 統計データ解析 / 生物情報学 / 医療統計 / 癌研究 / 創薬 / RNA-seq / シングルセルシーケンシング / PCA / クラスタリング / 遺伝子マーカー / バイオマーカー探索 / 肝臓病 / 

### Summary
大規模臨床検体のシングルセル解析は、生物学的な理解を深めるための強力なツールだが、実験者のテクニックやサンプルの保存状態などサンプリングバイアスがその解析結果に影響を及ぼす可能性がある。これは特に、細胞全体としての品質管理（QC）が適切であったとしても、特定の細胞集団、特に炎症が強い自然免疫細胞（例：モノサイト）が問題となりうる。これらの細胞は、RNase活性が高い、粘性が高いなどの理由から、他の細胞種に比べてサンプリングバイアスの影響を強く受ける可能性がある。この問題を解決するために、バイアスの程度を評価する指標を開発し、異なるコホート間での結果の再現性を評価した。

### Method
- COVID-19患者のシングルセルシーケンスデータを文献検索を行い、Rayyanツール上でシステマティックレビューを実施した。
- 各コホートで得られたデータをリストし、それぞれのwebページからダウンロードされるスクリプトを作成・実行をした。
- 前向きコホート研究を通じて、異なるコホート間（コホートA、B、C等）での結果の再現性を評価。これらのコホートで得られた結果が、既存のNatureやCellで報告されている研究結果と一致するか、また、それぞれのコホート間で結果が再現可能であるかを検証する。

### Contribution
本研究の実験の設計、データのダウンロードと処理、データ分析スクリプトの作成、データの解釈、図表の作成を行い、現在も主要な論文のテキストを執筆している。
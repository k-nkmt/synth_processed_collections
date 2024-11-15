# 国勢調査の匿名データのサンプル

データの仕様等は https://www.nstac.go.jp/use/archives/anonymity/kokucho/ を参照してください。

上記リンク先にあるデータレイアウト・符号表の仕様に沿って生成したデータです。
生成AIを利用して、以下のような構成の世帯を仮定してデータを生成したものになります。

- 夫婦+子供1人
- 夫婦のみの若い世帯
- 夫婦のみの高年齢の世帯
- 3世代(親世代+夫婦+子供)の世帯
- 働いている単身者の世帯
- アルバイトをしている学生の単身者の世帯

使用したモデルはGPT-4 0613相当で、作成当時ではAPIが利用できなかったためGUIから操作したものを、確認・調整したものになります。  
復号した後は基本的にいずれの年次でも同じ値・内容になります。  

## Sample of Anonymized Census Data

For data specifications, please refer to https://www.nstac.go.jp/use/archives/anonymity/kokucho/.

This data is generated according to the data layout and codebook specifications available at the above link.
Using generative AI, the data is created assuming households with the following structures:

- Couple with one child
- Young couple without children
- Elderly couple without children
- Three generations (parents + couple + child) household
- Single working individual household
- Single student working part-time household

The model used is equivalent to GPT-4 0613, and since the API was not available at that time, the data was generated through GUI operations, then reviewed and adjusted.
After decryption, the values and content will generally be the same for any year.
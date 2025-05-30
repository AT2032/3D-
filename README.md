# 3Dプリンターの使い方について
電装の部室には3Dプリンターがあります。  
今後，機体の作成などで使う場合はここの使い方を見て使うようにしてください  
もし，3Dプリンターが壊れた場合は電装の班の人に言うようにしてください  
![Image](https://github.com/user-attachments/assets/00366d2b-4866-4f94-afe1-720174874db3)
<img src="https://github.com/user-attachments/assets/00366d2b-4866-4f94-afe1-720174874db3" height="500px">

3Dプリンターとは3DCADの設計データ（STLデータ）をもとにして、スライスされた2次元の層を1枚ずつ積み重ねていくことによって、立体モデルを製作する機械のことを指します。  
ここから実際に3Dプリンターで3Dのデータを出力するまでの手法をやっていきます  
まず，CADの3DデータからSTLデータ(設計データ)を出力していきます。(今回はfusion360を使って行っていきます)
![Image](https://github.com/user-attachments/assets/b077b12c-01b2-4398-833d-048cf5336343)
出力できました(パソコン内にSTLファイルが作成されていると思います)
![スクリーンショット 2025-05-20 204119](https://github.com/user-attachments/assets/6ab74eb4-025f-4399-ae65-b22ac4bbae89)
ただ，このSTLファイルを3Dプリンターに読む込ませるだけでは、3Dプリンターで印刷することはできません。  
「スライサーソフト」というものを使い、3Dプリンターが3Dデータを読み込めるよう、変換する必要があり、スライサーソフトで得られる「Gコード」によって、はじめて3Dプリンティングが可能になります。  
部室にある3Dプリンターの種類は[Creality K1](https://www.creality.com/jp/products/creality-k1-3d-printer) です。  
このプリンター専用のスライサーソフトは

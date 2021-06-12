
# Grove用I2C通信距離延長モジュール（2個セット）

<img src="/images/product_photo.jpg" width="300px">  

NXP社の高ドライブ電流型のI2CバスバッファPCA9600Dを用いてI2Cの信号線の許容負荷容量を増加させ、I2C接続のGroveモジュールの通信距離を延長するためのモジュールです。  
基板同士は一般的なストレート結線のLANケーブルで接続します。LANケーブルは入手性が良いため、マイコンとGroveモジュール間の通信距離が数m～数10mのシステムを容易に構築できます。  

本製品は[Grove用I2C通信距離延長基板（2個セット）](https://github.com/y2kblog/Grove_I2C_Extension)のバージョンアップ版です。基板上に予め部品を実装することで組立の手間を低減しました。基板外形は変わらないため、従来品から容易に置き換え可能です。  
また、3D CADデータもダウンロードいただけます。  
<img src="/images/connection.jpg" width="600px">  


## 販売  
[スイッチサイエンス委託販売ページ](https://www.switch-science.com/catalog/7251/)  
※大量注文や在庫に関する問い合わせは[こちら](mailto:info.y2kb@gmail.com)までご連絡ください。  

## 内容物  

<img src="/images/package_contents.jpg" width="450px">  

## 別途ご用意いただく物  

- <a href="https://www.switch-science.com/catalog/2376/">PCA9600D 高ドライブ電流I2Cバスバッファ基板</a>
- Groveケーブル
- ストレート結線のLANケーブル（**<font color="Red">※クロス結線のLANケーブルを使用するとVCCとGNDがショートするため使用しないでください</font>**）

## 回路図  

<img src="/images/schematic.png" width="600px">  


## 接続例  
<img src="/images/connect_example.jpg" width="400px">  

30mのCAT6 LANケーブルを用いて通信テストを行い、Fast mode(400kbps)で問題なく通信できました。

## 組立方法  
1. 別途ご用意いただいたPCA9600D基板に付属の細ピンヘッダをはんだ付けします。
   <img src="/images/pca9600d_pcb_soldering.jpg" width="120px">  
1. PCA9600D基板上のシルクと延長基板上のシルクが一致する向きにICソケットに挿します。  
   <img src="/images/assemble_1.jpg" width="250px">  

## 資料  
### 基板寸法  
<img src="/images/pcb-dimensional-drawing.png" width="280px">  

### CADデータ  
- [3Dモデル閲覧（Sketchfab）](https://sketchfab.com/3d-models/grovei2c-9ce9cb5161b94b47932790ef6c42111e)  
- DXFファイルダウンロード：<a href="https://github.com/y2kblog/grove-i2c-ext-mod/raw/master/resources/dimensional_drawing_dxf.zip" download="">dimensional_drawing_dxf.zip</a>  
- STEPファイルダウンロード：<a href="https://github.com/y2kblog/grove-i2c-ext-mod/raw/master/resources/3d_model_step.zip" download="">3d_model_step.zip</a>  

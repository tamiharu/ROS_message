# ROS_message

## 概要    
ファイル名【scripts】内にある【count.py】と【twice.py】を使ったメッセージを表示するパッケージです。

## 動作環境 
・OS：Ubuntu 20.04  
・ROS1

## 実行方法
**パッケージを構築する**
```
cd ~/catkin_ws/src
git clone https://github.com/tamiharu/ROSROS.git
cd ~/ROS_message
catkin_make
soource ~/.bashrc
```

## 実行方法
このパッケージを実行する際には端末が３つ必要になるのでそれぞれの操作方法を解説します。
### ・端末１
ROSを有効にします。  
```roscore```

### ・端末２
2つあるノードのうちの一つ【count.py】を起動します。  
```rosrun mypkg count.py```  
起動した後、何も表示されませんが、実行できているのでそのままにしておきます。  

### ・端末３
最後にもう一つのノードである【twice.py】を起動します。  
```rosrun mypkg twice.py```

## 動作結果（動画）  
動作した結果をyoutubeにて公開しています。  
[動画](https://www.youtube.com/watch?v=_PnO3ojpHpU)  

## その他(ライセンス、著作権者等)
・ライセンス：[BSD 3-Clause License](https://github.com/tamiharu/ROS_message/blob/main/LICENSE)  
・著作権者：上田隆一(Ryuichi Ueda)

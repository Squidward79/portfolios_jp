# LEE HOMINのプログラミング記録
今まで制作したプログラムの説明や写真です。


## 1. RayTracing
<div>
<img width="350" src = "https://user-images.githubusercontent.com/45874696/67154395-ce833680-f336-11e9-8548-ac0d983bfce1.png">
</div>

 使用ツール： VisualStudio / C++ / OpenGL

#### 説明 
 backward方法を使うRayTracingプログラムです。 </br>
 光の反射と屈折を適用しました。
 照明モデルはPhong公式を利用し、表現しました。



 ---
  
## ２. RayCasting
<div>
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154388-9bd93e00-f336-11e9-980f-8054df29ede0.png">
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154374-3a18d400-f336-11e9-8ba8-f8bfafba780c.png">
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154377-50269480-f336-11e9-91c2-0dad29a50bc0.png">
</div>

 使用ツール： VisualStudio / C++ / OpenGL

#### 説明</br>
人の断層撮影イメージを合わせて３Dモデルを作り出す RayCastingプログラムです。</br>
３Dモデルの皮膚や皮膚の中にある骨を見られる機能とモデルを回転しながら見られる機能があります。</br>
照明モデルはPhong公式を利用しました。
  
---
  
## 4. CUDA Programming
<div>
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154576-acd77e80-f339-11e9-819b-c423a81bdf43.png">
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154577-b6f97d00-f339-11e9-9b15-ce81ffd01baa.png">
<img width="280" src = "https://user-images.githubusercontent.com/45874696/67154578-c11b7b80-f339-11e9-999e-242a676a0b83.png">
</div>

 使用ツール： VisualStudio / C++ / CUDA / OpenCV

#### 説明
  CPUとGPUの映像処理の速度を比べるプログラムです。同じ映像についてGPUはCUDAを利用し、並列で演算を処理しました。
  運転手目線で高速道路を走行する映像から車線を検出して直線で見せることやガウシアンフィルタのようなフィルタを入れることができます。</br>
  結果的にCUDAを使ってCPUより20倍の性能が向上することを経験しました。
  
---
  
## 4. 卒業作品

<img width="500" src = "https://user-images.githubusercontent.com/45874696/67154474-1fdff580-f338-11e9-885b-58f13cc7979a.png">
<img width="500" src = "https://user-images.githubusercontent.com/45874696/67154482-3be39700-f338-11e9-86c2-61f08bfa4876.png">

 使用ツール： Unity3D / C＃ / VIVE PRO
 
#### 説明

卒業作品でVIVE PROを使って仮想のMIDI楽器LaunchPadをMR環境で演奏できるプログラムと、スマホがVIVEと同時に合奏できるアプリケーションです。
周辺の空間を認識して現実基盤のMeshを作ります。演奏する時に生成されるParticleが現実のイメージに相互作用します。Meshの生成はVIVEで提供するAPIを使用しました。
  

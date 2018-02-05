# MHD2018HapTune
MUSIC HACK DAY TOKYO 2018  HapTune  
https://entertechlab.jp/p/32

Max Patch 

Maxで作ったもの  
 音楽ステム再生、照明コントロール、OSC（for Unity)  

- OSC 
年号を/rampで（Touchのがそうだったのでとりあえず）  
1972 Pong, 　(12  最長48sec　、最短24-6 =18sec)  
1984 FC,　　(23　最長92sec、最短46-11 =35sec)  
2007 PCM ,    (10　最長40sec、最短20-5 =15sec)  
2017 EDM,    (28　最長112sec、最短56- 14=42sec)  
2045 END と曲が切り替わります。 (全　最長 292sec（4分弱）　最短82sec(1分半))  

/k1~ /k7に0,1で押しているかの状態、  
押している時だけそのトラックの音がメイン(8ch）から出力されます。  
1~7chは常に振動用の音声が出続けています。  

- 年の変化  
6人以上が押している状態で年の進み具合が早くなります。(2sec毎）  
何も押していなくてもゆっくりと年号は増えていきます。(4sec毎)  

- 振動  
Pong,Endは７人すべて同じ信号で振動します。  
FC,PCM,は自分の信号だけ振動します。  
EDMは自分の信号とバスドラの信号が混ざって出ています。  

- バックトラック  
FC,PCM,EDMにはバックトラック（FC,PCMはハイハット　EDMはバスドラ）が、誰も押していなくてもガイドとして鳴っています。  

- サウンド  
振動トラックは個別再生可能にしてあって、  
全て低音強調しています。(7tk * 3 = 21trk + 5trk = 26trk)  
8chから出力するMix音は低音をハイパスフィルターで減らしています。（モノラルMix)    
（音素材に大量の低音成分が含まれているため、普通に再生すると音が歪みます。）  

-　コントロール  
　MIDI NOTE NO 41 - 44,57 - 59　（LAUNCH PAD Control）  
　PC Key 1-7  
それぞれサウンドトラックのON/OFFできます。  


[パプビート7個使った作品を作った。]   
https://twitter.com/stake2722/status/960060263880798208   
[Mufoキャラの変遷]   
https://twitter.com/stake2722/status/960081624862830597   
[MuFoのシャツ貰った！]   
https://twitter.com/MuFoApp/status/960121264546381824   
[揺れたり 光ったり 音が出たり]   
https://twitter.com/tatmos/status/960075269859024896   
[Max と細かいSTEM素材　とマルチアウト]   
https://twitter.com/tatmos/status/959914272657522688   
[曲構成、画面構成ラフスケッチ]   
https://twitter.com/tatmos/status/960060488477417472   

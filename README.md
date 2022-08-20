# RIME Inputting Method of Sautungva<br>基於rime平臺的邵東話輸入方案

#### 介绍
rime邵東話輸入方案為基於國際音標個湘語邵東話輸入法。  
如果你曉得國際音標IPA就蠻容易理解本輸入法跟邵東話個讀跟說。  
This is an inputting method of Sautungva, the Xiang Chinese dialect, mostly based on IPA, with which you can soon learn to type, read and speak

#### 安装教程

1.  將同一組兩個yaml文件放入rime的【**用戶文件夾**】中。
2.  找到用戶文件夾中一個名叫【**default.custom.yaml**】的文件，打開（可以使用notepad++或者VS，pycharm之類的軟件打開，或者修改文件擴展名為.txt後由記事本打開，隨後再内部添加上本輸入法的名稱【**\- saudungva**】，與其他幾個輸入法對齊，格式一致。
3.  點擊【**輸入法配置**】選中該輸入法，【**重新部署**】后即可使用。 

#### 使用说明

邵東話方案

1.  本方案基於國際音標進行表示，在表示上極爲接近國際音標。輸入時以不帶聲調輸入但顯示聲調。具有普通話拼音反查功能。
2.  聲母：**p ph b k kh g t th d s z c ts tsh dz tc tch x h f v l m n ng**<br>注意聲母清送氣不送氣濁音三分（**tc**跟**ts**箇濁音合為一隻**dz** 且輸入時 **n l** 不做區分一律以 **l** 做表示，**n** 表示孽的聲母
3.  韻母：**a o e i u y ai an ang au en ei eu ia ie in ien iau ieu ian iang ien uen uei ung uai uang yn ye yen ya**
3.  當前版本具有一定的容錯空間，允許**ou**表示**eu**，**ui**表示**uei**等
4.  反查：對於不確定的字可以通過【TAB】鍵上方的【\`】鍵進行反差，比如對 在 字反差，輸入【\`zai】後候選字將出現【在 dzai5】可以知道通過zen可以輸入【在】字
5.  **當前版本的輸入法收字不夠全面，未進行詞語編寫，可能存在相當多的問題，歡迎各位通過QQ或者郵箱與我聯係提供對該輸入法的改進意見**

邵東話拼音方案

1.  本方案在表示上接近於現行漢語拼音方案，以雙寫表示濁音
2.  聲母：**p b bb k g gg t d dd s r z c zz j q jj x y h hh f v l m n ng**<br>注意聲母清送氣不送氣濁音三分 且輸入時 **n l** 不做區分一律以 **l** 做表示，**n** 表示孽的聲母
3.  韻母：**a o e i u y ai an ang ao en ei ou ia ie in ian iao iu ian iang ien uen uei on uai uang yn ye yen ya**
3.  當前版本具有一定的容錯空間，允許**un**表示**uen**，**清音**也匹配**濁音**等
4.  反查：對於不確定的字可以通過【TAB】鍵上方的【\`】鍵進行反差，比如對 在 字反差，輸入【\`zai】後候選字將出現【在 zzai5】可以知道通過zen可以輸入【在】字
5.  **當前版本的輸入法收字不夠全面，未進行詞語編寫，可能存在相當多的問題，歡迎各位通過QQ或者郵箱與我聯係提供對該輸入法的改進意見**

#### 参与贡献

1.  本輸入法由`轀輬[alfredlouis0x7@gmail.com； QQ：1739415287 （郵箱同）]`製作。
2.  漢字讀音參照**漢字音典**與 黃磊.邵東湘語語音研究[D].長沙:湖南師範大學,2005

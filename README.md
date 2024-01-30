# RIME Inputting Method of Sautungva<br>基於rime平臺的邵東話輸入方案

- [RIME Inputting Method of Sautungva<br>基於rime平臺的邵東話輸入方案](#rime-inputting-method-of-sautungva<br>基於rime平臺的邵東話輸入方案)
  - [介绍](#介绍)
  - [安装教程](#安装教程)
    - [電腦 Windows 小狼毫](#電腦-windows-小狼毫)
    - [手機 Android 同文/中文](#手機-android-同文中文)
  - [使用说明](#使用说明)
    - [邵東話方案(`sautungva`, `sautngva_beta`)](#邵東話方案sautungva-sautngva_beta)
    - [邵東話拼音方案(`sautungva_phinin`)](#邵東話拼音方案sautungva_phinin)
    - [邵東話西里爾方案(`sautungva_cyrillic`)](#邵東話西里爾方案sautungva_cyrillic)
  - [参与贡献](#参与贡献)

## 介绍

rime邵東話輸入方案為基於國際音標個湘語邵東話輸入法。  
如果你曉得國際音標IPA就蠻容易理解本輸入法跟邵東話個讀跟說。  
This is an inputting method of Sautungva, a Xiang Chinese dialect, mostly based on IPA, with which you can soon learn to type, read and speak

## 安装教程

### 電腦 Windows 小狼毫

1.  將同一組兩個yaml文件放入rime的【**用戶文件夾**】中（當然放兩組也可以）。
2.  找到用戶文件夾中一個名叫【**default.custom.yaml**】的文件，打開（可以使用notepad++或者VS，pycharm之類的軟件打開，或者修改文件擴展名為.txt後由記事本打開，隨後再内部添加上本輸入法的名稱【**\- saudungva**】（或【**\- sautungva_phinin**】，取決於你放入的文件），與其他幾個輸入法對齊，格式一致。
3.  點擊【**輸入法配置**】選中該輸入法，【**重新部署**】后即可使用。 

### 手機 Android 同文/中文

1.  將同一組兩個yaml文件放入【**rime**】文件夾中（當然放兩組也可以，同名的 dict 和 schema 為一組）。
3.  進入同文輸入法 點擊【**輸入**】然後點擊方案，選中該輸入法，再打開同文點擊【**部署**】后即可使用。

## 使用说明

**輸入方案詳情也可以參考本人[知乎文章](https://zhuanlan.zhihu.com/p/625434395)**

### 邵東話方案(`sautungva`, `sautngva_beta`)

1.  本方案基於國際音標進行表示，在表示上極爲接近國際音標。輸入時以不帶聲調輸入但顯示聲調。具有普通話拼音反查功能。
2.  使用時請將以`stv`開頭多個`dict`文件以及`tcyennie.dict.yaml`, `thezy.dict.yaml`一併放入對應文件夾使用
3.  聲母：**p ph b k kh g t th d s z c ts tsh dz tc tch x h f v l m n ng**<br>注意聲母清送氣不送氣濁音三分（**tc**跟**ts**個濁音合為一隻**dz** 且輸入時 **n l** 不做區分一律以 **l** 做表示，**n** 表示孽的聲母。
4.  韻母：**a o e i u y ai an ang au en ei eu ia ie in ien iau ieu ian iang ien uen uei ung uai uang yn ye yen ya** (聲母與韻母表中以紅色標記。
5.  聲調：以 **q r w j**分別輸入**1 2 3 45**聲。考慮到按鍵不足而對於去聲一般人沒有區分的意識且陰陽去聲不會同時出現，故以j同時輸入陰陽去。
6.  當前版本具有一定的容錯空間，允許**ou**表示**eu**，**ui**表示**uei**等。
7.  反查：對於不確定的字可以通過【TAB】鍵上方的【\`】鍵進行反差，比如對 在 字反查，輸入【\`zai】後候選字將出現【在 dzai5】可以知道通過dzai（或者dzaij可以更精準地輸入）可以輸入【在】字。
8.  **當前版本的輸入法收字不夠全面，未進行詞語編寫，可能存在相當多的問題，歡迎各位通過QQ或者郵箱與我聯係提供對該輸入法的改進意見**。

### 邵東話拼音方案(`sautungva_phinin`)

1.  本方案在表示上接近於現行漢語拼音方案，以雙寫表示濁音。
2.  聲母：**p b bb k g gg t d dd s r z c zz j q jj x y h hh f v l m n ng**<br>注意聲母清送氣不送氣濁音三分 且輸入時 **n l** 不做區分一律以 **l** 做表示，**n** 表示孽的聲母。
3.  韻母：**a o e i u y ai an ang ao en ei ou ia ie in ian iao iu ian iang ien uen uei on uai uang yn ye yen ya** (聲母與韻母表中以藍色標記。
3.  當前版本具有一定的容錯空間，允許**un**表示**uen**，**清音**也匹配**濁音**等。
4.  反查：對於不確定的字可以通過【TAB】鍵上方的【\`】鍵進行反差，比如對 在 字反查，輸入【\`zai】後候選字將出現【在 zzai5】可以知道通過zzai可以輸入【在】字。
5.  **當前版本的輸入法收字不夠全面，未進行詞語編寫，可能存在相當多的問題，歡迎各位通過QQ或者郵箱與我聯係提供對該輸入法的改進意見**。

### 邵東話西里爾方案(`sautungva_cyrillic`)

1. 本方案建議在安卓手機上配合`tongwenfeng_custom_cyrillic.trime`主題使用。
2. 使用時請放入`sautungva.dict.yaml`和`sautungva_cyrillic.schema.yaml`。
3. 可以使用反查（但是由於鍵位問題可能不太好用）
4. 聲母韻母等參考邵東話方案和知乎文章。

## 参与贡献

1.  本輸入法由`轀輬[alfredlouis0x7@gmail.com； QQ：1739415287 （郵箱同）]`製作。
2.  漢字讀音參照**漢字音典**與 黃磊.邵東湘語語音研究[D].長沙:湖南師範大學,2005
3.  本輸入法製作過程中受到了許多前輩及朋友的幫助，如B站UP主`shinsoqchiuq`,QQ群的`恋伊`以及邵語微信群`大江游鱼`的幫助
4.  本輸入法拼音版參考了邵語群`潇湘竹客`的邵陽話轉寫方案

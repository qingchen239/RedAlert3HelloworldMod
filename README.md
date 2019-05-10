# 紅色警戒3 helloworld模組  
這是我做的第一個《紅色警戒3》模組。  
## 說明  
我做這個模組的初衷是用來好友之間的聯機對戰。  
在如今的中國大陸，好友之間進行《紅色警戒3》的聯機對戰時大多都是借助**浩方电竞平台**完成的。  
但是，在**浩方电竞平台**對戰時，常常會因為有路人玩家誤入您的對戰房間而造成不便。  
由於《紅色警戒3》的對戰有着這樣的特性：安裝有不同模組的玩家不能進入同一房間。
於是，我開發了一款用來聯機的模組，即幾乎不在原版的基礎上做任何修改，僅用於聯機對戰使用。  
但是這樣似乎有一點太無聊了，所以我給遊戲中最不起眼的地方——三軍的**發電站**（PowerPlant）——加入了一個變成**將軍劊子手**（JapanMechaKing）的能力，以此來對戰時給您的好友以驚喜。  
不過蘇聯的**超級反應堆**（SovietPowerPlantAdvanced）不能變成**將軍劊子手**，反而會變成遊戲中最菜的步兵——**動員兵**（SovietAntiInfantryInfantry）。  
## 使用方法  
### 用來遊玩  
**helloworld.rar**是將這個模組經過**RA3 MODSDK-X**編譯後生成的文件壓縮而成的。  
您將它解壓並放到遊戲的**mod**文件夾下，並按照打開遊戲mod的方式正常打開就可以玩了。
### 用來編譯  
而**helloworld**文件夾裡面存放着的是這個模組的原文件。  
您可以將它們放在**RA3 MODSDK-X**下的**Mods**文件夾中，並用**EALAModStudio.exe**編譯它。  
在編譯的時候需要在**Mod Build Option**選擇**05.建立基础数据**、**09.建立Big文件**、**10.建立Skudef文件**和**12.建立窗口INI文件**。  
在編譯時可能會顯示出現一串**Unknown asset**的**Warning**，並且在遊戲中出現的**將軍劊子手**顯示不出來。如果出現這種情況的話，請安裝**sdk worldbuilter**並在編譯時在**Mod Build Option**選擇**07.修复中立资产**。這時編譯還是會出現**warning**，但是**將軍劊子手**已經可以正常顯示了。    
  
## 其它
這是我第一次寫模組，還有很多地方處理得不好。還請各位見諒。  
在我最初的想法中，我想把**超級反應堆**變**動員兵**時加入一個反應堆爆炸的效果並對周圍單位與建築造成傷害，但是由於本人能力有限，並沒有做出來。  
在我寫這個模組的過程中，來自中國大陸的**RAT红警社区**的**zyb**同志、**Ngen**同志、**0010明天战网更新吗**同志以及社區裡的其它同志們給予了我巨大的幫助，在此向他們表示感謝。  

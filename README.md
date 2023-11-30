# 育苗場環控與植株育成率推論模型 Greenhouse environmental control and seedling growth rate inference model
* 此模型利用各個控制器與室外溫度、濕度、光照度，即可預測室內溫度的均勻度。
* 輸入: 各個控制器與室外溫度、濕度、光照度，代號比對表另提供
* 輸出: 10分鐘後的室內溫度的均勻度

* 使用步驟如下:  
0.電腦若沒有python 與pip套件，需先下載  
1.前往存取資源，進入雲端連結，下載檔案會是一個壓縮檔，解壓縮得到一資料夾  
2.開啟資料夾所在位置的終端機(cmd)  
3.首先安裝相關套件，輸入pip install -r requirement.txt  
4.而後將資料按照"input_data.csv"的格式，寫入控制器與室外溫溼度資料  
5.輸入python demo.py，執行模型  
6.輸出室內溫度的均勻度結果，並存儲於"output.txt"  

附錄:  
Output: 未來10分鐘時，溫室中的"溫度均勻度"   
Inputdata(溫室中各個控制器狀態):  
雙程1(on)/單程1(off) 'machineId': '62593898aae37d0e4ee20ee0'  
去有水1（on)/去無水(off) 'machineId': '62593937aae37d0e4ee20f61'  
回有水1(on)/回無水1(off) 'machineId': '62593970aae37d0e4ee20f94'  
手動去1 'machineId': '6259398daae37d0e4ee20f95'  
手動回1 'machineId': '625939c3aae37d0e4ee20ff7'  
停止1 'machineId': '625939c8aae37d0e4ee20ff8'  
雙程2(on)/單程2(off) 'machineId': '62593a03aae37d0e4ee21018'  
去有水2（on)/去無水(off) 'machineId': '62593a25aae37d0e4ee2102a'  
回有水2(on)/回無水2(off) 'machineId': '62593a3faae37d0e4ee2102c'  
手動去2 'machineId': '62593a60aae37d0e4ee2106a'  
手動回2 'machineId': '62593a6eaae37d0e4ee21091'  
停止2 'machineId': '62593a83aae37d0e4ee21093'  
雙程3(on)/單程3(off) 'machineId': '62593ad7aae37d0e4ee210c1'  
去有水3（on)/去無水(off) 'machineId': '62593aefaae37d0e4ee210cd'  
回有水3(on)/回無水3(off) 'machineId': '62593b15aae37d0e4ee2111c'  
手動去3 'machineId': '62593b1aaae37d0e4ee21154'  
手動回3 'machineId': '62593b2eaae37d0e4ee2115e'  
停止3 'machineId': '62593b34aae37d0e4ee2115f'  
北卷揚 'machineId': '62591e88aae37d0e4ee1ff2b'  
西北上卷揚 'machineId': '62591eabaae37d0e4ee1ff53'  
西北下卷揚 'machineId': '62591ed9aae37d0e4ee1ff5c'  
西南上卷揚 'machineId': '62591eebaae37d0e4ee1ff5f'  
西南下卷揚 'machineId': '62591efeaae37d0e4ee1ffa5'  
南上卷揚 'machineId': '62591f1faae37d0e4ee1ffac'  
南下卷揚 'machineId': '62591f39aae37d0e4ee1ffad'  
東南上卷揚 'machineId': '62591f53aae37d0e4ee1ffbf'  
東南下卷揚 'machineId': '62591f6baae37d0e4ee1ffd2'  
東北上卷揚 'machineId': '62591f82aae37d0e4ee1ffd4'  
東北下卷揚 'machineId': '62591f98aae37d0e4ee1ffd9'  
遮陰網1  'machineId': '62591fc2aae37d0e4ee2001a'  
遮陰網2  'machineId': '6259201eaae37d0e4ee20030'  
負壓風扇1  'machineId': '62592076aae37d0e4ee20069'  
負壓風扇2  'machineId': '6259208caae37d0e4ee2006c'  
內循環風扇1  'machineId': '625920b0aae37d0e4ee2006d'  
內循環風扇2  'machineId': '625920c2aae37d0e4ee20091'  
內循環風扇3  'machineId': '625920d4aae37d0e4ee2009a'  
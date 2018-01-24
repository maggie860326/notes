# (Ch3) Neurophysiology

## 章節 FOUCS
- 神經元激發、傳導的基礎:離子機制
- 突觸傳遞Synaptic Transmission
- 化學突觸傳遞過程中的序列
- 離子通道、突觸、神經傳遞物之演化
- 神經元與突觸結合而產生的神經回路

----
## 電流模式之神經細胞傳遞
-  生物電能的發現 
    -  由Calvani解剖青蛙，用靜電刺激蛙神經，能引起與其連接的肌肉收縮 
    -  發現神經的電傳導現象
    -  電鰻: 具有特化的肌肉形成「肌電板」
    
- 神經細胞膜電位
    - 電訊號產生原因:神經細胞膜具有電位興奮性( Electrical Excitability)
    - 靜止時則稱之靜止膜電位 (Resting Membrane Potential)

![](https://i.imgur.com/jiNKwSN.png)


---
## 膜電位之形成因素

1. 細胞內外之溶液離子 
    -  水：H^+^、O^-^ 以極性共價鍵Polar Covalent Bond結合 => 極性溶劑   
    -  離子 : 離子鍵結合 => 溶液中形成正離子 Cations、負離子 Anions   
    -  擴散 Diffusion
2. 膜的通透性
    - 膜由2層磷脂質 (Phospholipid Bilayer) 組成
        - 極性端 (polar head)：磷酸根為親水性(hydrophilic)。
        -  非極性端 (nonpolar chain)：脂肪酸由碳鍊的非極性共價鍵形成，為疏水性(hydrophobic)。
    - 組成類似電容Capacitor結構
3. 細胞膜上的蛋白質結構
      - 受體 Receptors
      - 離子管道 Ion Channels
      - 轉運子 Transporter、幫浦Pump

---
## 靜止膜電位
擴散壓力 (diffusion force)和靜電力 (electrostatic force)達到整體平衡

靜止膜電位主要是K^+^達到平衡，因為Na^+^的滲透性很低。

### 性質:
- 極少的離子移動即可導致很大的膜電位改變。
- 細胞膜是一個電容板(Capacitor，兩層導體隔著一層很薄的絕緣體，可以儲存電荷)，因此所有的電荷差異會平均分佈在表面。
- 不同種類之離子達到進出平衡時的電位不同，此謂之為該離子的平衡電位(Equilibrium Potentials)。
- 靜止膜電位為： -50 ~ -80 millivolt (mV)

### 神經細胞內外離子濃度差異

- 外部有較多氯離子(Cl^-^)、鈉離子(Na^+^)、鈣離子(Ca^2+^)。
- 內部有較多的鉀離子(K^+^)、蛋白質負離子(Anion)
- 離子分布不均勻

### 計算靜止膜電位
- Nernst Equation:
計算單一種離子造成的膜電位
$$
E_x= \frac{58}{離子X的電荷}mV\times \log \frac{X在膜外的濃度}{X在膜內的濃度}
$$
例如: K^+^離子，膜外濃度$5mM$，膜內$140mM$
$$
E_{K^+}=58mV\times\log\frac{5}{140}\approx 58mV\times-1.45\approx-83.94mV
$$
- Goldman Equation:
考量了其他離子以及每個離子對膜的通透性，計算結果較接近真實的膜電位-60mV



----
## 離子通道 Ion Channel
![](https://i.imgur.com/CsVhEVB.png)

![](https://i.imgur.com/stbVWoD.png)

- 特性
    - 每個離子都有其專門的通道
  - 選擇性通透性
  - 分為Passive、Active通道，其兩種功能、分佈區域皆不同
- <font color=blue>**被動式通道 Passive channel**</font>
     - 順著梯度進行滲透，不需要修耗能量
     - 與建立靜止膜電位(RMP)有關
     - 例 : Leak Channel洩密渠道(常開啟型)
    - 門控通道 (Gated channel)，只有特定條件之下才會開啟 
        1.  **配體閘門控制型通道 Ligand-Gated Ion Channel**
            -  分布在接受區(包含Dendrites、Cell body)
            -  這類的通道在特定的配體分子附著在受體蛋白在細胞外結構部分之後才會打開
            -  配體和受體的結合會改變通道蛋白結構的構象改變，並最終打開通道讓離子穿過細胞膜

      2. **電壓閘門控制型通道 Voltage-Gated Channel**
            -  平常關閉，當電壓到達閾電位時開啟，產生動作電位 Action Potentials
            -  分布在軸突丘、整條無髓鞘軸突、朗氏節
            -  動作電位的產生是在有電壓閘門控制型的通道分佈之處(Na+、K+電壓型通道)
            - 對細胞膜電位差的改變敏感，因膜電位的改變導致通道的開啟、關閉。

- <font color=blue>**主動式通道 Active channel**</font>
    - 逆著梯度進行運輸，需要消耗能量
    - **鈉鉀幫浦 Na^+^/K^+^-ATPase**，形成靜止膜電位
![](https://i.imgur.com/C4iw371.png)
![](https://i.imgur.com/3CQKKZU.png)
  


### 鉀離子通道 K^+^ Channel
- 通道
  - 被動性鉀離子通道Passive K^+^ Channel
  - 電壓控制型鉀離子通道 Voltage-Gated K+ Channel  
  - Roderick MacKinnon
    - a) 心跳頻率、神經衝動
    - b) 利用X射線晶體學得到電壓控制型 K +通道的第一個高分辨率3D圖像

- 控制鉀離子濃度之安全閥
  - 膜電位高低取決於胞內外離子濃度差異: chemical gradient
  - 鉀離子(K+)濃度在胞外的上升
  - 上升十倍，膜電位由-65 mV上升至-17 mV: 超過細胞膜產生活動電位的閾限，所以神經就會不斷的興奮
  - 為防止胞外鉀離子濃度過高，神經系統有兩個重要的機制:
    -  Na^+^ K^+^ ATPase Pump: 3鈉出，2鉀進
    -  Potassium Spatial Buffer: 星狀膠細胞(Astrocyte)會聚斂神經元外的鉀離子 
  - 利用這個特性來興奮神經組織，但是這種興奮最後會導致神經活動完全消失(excitotoxicity)
![](https://i.imgur.com/yuuhGKb.png)



### 研究離子通道方法
- #### 物理性質
    - **X光晶體繞射學 (X-ray Crystallography)**
     - 蛋白質純化 -> 誘使其產生結晶 -> 結晶物受X-ray照射 -> 產生繞射圖型 -> 電腦計算蛋白質結構模型 
- #### 生理性質
    - **Voltage Clamping**
        - 比較膜電位和實驗者預設的目標電位，如果兩者不一致，便會對Axon注入電流，發生動作電位時，量測注入的電流變化便可知Na+離子流動的多寡。


    - **Patch Clamping**
      - Neher、Sakmann創造
      - 記錄通過離子通道的電流来反應細胞膜單一or多個的離子通道活動的技術
      - 當膜電位從 – 65 mV to –40 mV時，鈉離子管道便會開啟
      -  開啟的潛伏期很短，開啟的時間很短 (1 秒) 旋即閉鎖。
      -   ㄧ旦閉鎖除非膜電位重新回到極化前的負值，否則不能再開
      -    單一個鈉離子管道並不能造成活動電位
      -    每100-600 Na+ channel/mm giant squid axon，每開一秒容許10億個Na+進入

![](https://i.imgur.com/C6hPcqQ.jpg)
![](https://i.imgur.com/dCOZFkY.jpg)
![](https://i.imgur.com/H10rwAO.png)


-  #### 藥理性質
      - 通道病變(Channelopathy):編碼離子通道的基因
        - 例: 鈉通道病變 -> 癲癇發作
      - 利用特定毒素能阻斷特定離子通道之特性:
        -  Block Channels
        -  Unblock Channels

      - 兩種藥物可以用來單獨研究離子的行為:
        -  **Na+ channel blockers: 阻斷鈉離子管道**
            -  TTX (Tetrodotoxin, 河豚毒素):
中毒主要以影響神經系統為主，可使神經及肌肉麻痺致死，毒力為氰化鉀 (KCN) 之4倍。

            -  STX (Saxitoxin):
由蛤、蠔類所產生之蛤蚌毒素，具有阻斷肌肉神經元及鈉傳導之作用。 
        -  **K+ channel blocker:阻斷鉀離子管道**
            - TEA (tetraethylamonium, 氫氧化四乙銨)


---

## 活動電位的產生
![](https://i.imgur.com/MgKDkVe.png)


### 離子機制

-  膜電位靜止時(不受刺激) 
    - 有一種K+離子管道開啟。
-  當神經受刺激時，**Na+離子**的管道開啟，鈉離子湧入 
    -  內部電位升至 +40 mV，為<font color=red>去極化 (Depolarization)</font>
-  Na+離子管道隨即閉鎖(Inactivated)。
-  另一類的**K+離子**管道稍後開啟，鉀離子湧出，將膜電位拉回。 
- 由於Na+離子管道閉鎖，沒有任何鈉離子進入 
    - 膜電位<font color=red>過極化 (Hyperpolarization)</font>時會直達K+離子的平衡電位 (-80 mV)。<font color=red>(Afterpotential、Undershoot)</font>
- 鈉離子管道閉鎖時，神經不能再產生活動電位 => <font color=red>絕對反挫期(Absolute Refractory period)</font>。
-  稍後鈉離子管道回復正常狀態，神經可接受刺激
    - 此時膜電位較低，需較大的刺激才能達到閾值 => <font color=red>相對反挫期(Relative Refractory period)</font>。 
-  神經衝動結束
    - 透過鈉鉀幫浦: 3Na+被排出，2K+進入
  
  
### 特性
(重發圖片，模糊不清楚)
![](https://i.imgur.com/Tmm2HgP.png)
![](https://i.imgur.com/e69SfxI.png)



## 活動電位的傳導

### 傳導方向
 - 除非是用人為方式在神經的中間或末稍刺激，否則活動電位一定是從細胞本體往軸突末稍的方向傳遞。
 - 活動電位沿著軸突主動地生成。

### 影響傳導速度的因素
- 神經軸突的粗細，越粗越快:
    - 粗的軸突內阻力較低，所以可以靠被動傳導(Na+離子擴散)的方式走較遠不致耗損太多。
-  膜電阻（Membrane Resistance）越低，則電流越易流到細胞之外。
-  膜電容（Membrane Capacitance）越高，則電流越易充滿電容不往前進。 
- 粗的神經除了傳導速率較快外，也較容易達到興奮的閾值:
    - 較大的表面積具有較多的Voltage-dependent ion channels
    - 細的神經需要較多的去極化，也較容易被藥物所阻斷
-  烏賊的巨大神經直徑約0.5-1mm是加粗神經以增進傳導速率的致極表現。更粗就會妨礙整個個體的容納平衡 

### 髓鞘

- 加速神經傳導、不加粗神經
- 減少膜電容: 降低停住於膜上的電量
- 增加膜電阻: 增加在神經軸突內傳導的電流 
- 禁止離子交換:Na^+^-K^+^幫浦不必運作
- 朗氏節 (node of Ranvier) 跳躍式傳導 (saltatory conduction)。

### 無髓鞘/有髓鞘的活動電位傳導
![](https://i.imgur.com/BrHGnjw.png)
![](https://i.imgur.com/PugSSnf.png)



### 活動電位胞內、胞外測量

![](https://i.imgur.com/Q46E1DW.png)
- 胞內測量(上面):
原本帶負電(上A)，活動電位到達時趨向正(上B)，離開時因過極化(上C)趨向負。

- 胞外記錄(下面):
正好相反，原本帶正電(下A)，活動電位到達時趨向負電位(下B)，離開時則因過極化(下C)趨向正電位，(下D)回復正常

---

## 化學模式之神經細胞傳遞
-  要旨
    - 任何的突觸使用化學物質傳遞訊息之所需機制:
      - 要有合成神經傳導素的機制
      - 神經傳導素必須封裝於囊泡Vesicles內
      - 要有釋放神經傳導素的機制
      - 神經傳導素要有作用的受體Receptors
      - 神經傳導素需有失去作用的機制
- 形式
    - 以突觸前與突觸後的位置區分
      - Axo-dendritic
      - Axo-somatic
      - Axo-axonic
      - Dendro-Dendritic
      - Others
- 傳遞 
    - 以化學物質傳遞訊息
      - 突觸(Synapse): 神經與神經間聯絡的結構。
      - 突觸溝(Synaptic Cleft): 神經突觸間的縫隙 (20 nm)，使得神經訊號需透過化學物質傳遞。
      - 神經傳導素 (Neurotransmitters): 在突觸間傳遞神經訊息的化學物質。
      - 神經調節素 (Neuromodulators): 調節神經傳遞功能的物質。
      - 突觸加成作用 (Synaptic Summation): 時間與空間。
      - 突觸電位 (Synaptic Potential):
        -  興奮性Excitatory postsynaptic potential (EPSP):
引發Na+進入細胞。
        - 抑制性Inhibitory postsynaptic potential (IPSP):
引發Cl-進入細胞


## 活動電位/EPSP/IPSP 的比較
![](https://i.imgur.com/Wctqngl.png)


## 突觸傳導
### 重要名詞
-  配體Ligand
    -   內源型配體Endogenous ligands: 神經傳導素、激素
    -    外源型配體Exogenousligands: 藥物、毒素、毒液
-  受體Receptor
    - 指傳導細胞信號的蛋白質，其能與ligand結合，觸發後續的生理反應。
-  Agonists: 增進神經傳導物作用的物質。
-  Antagonists: 干擾、阻止神經傳導物作用的物質。
-  外釋作用 Exocytosis 
    -  外釋作用將代謝產物或特殊分泌物 (如激素) 釋放到細胞外
-   內噬/胞飲作用 Endocytosis
    -   內噬作用則是將物體帶進細胞內部
    -  例：胞飲作用Pinocytosis ➡ 將小滴的胞外液體帶進細胞內部。
-  Up-regulation
    - 增加receptor數量，增大效果。
- Down-regulation
    - 減少receptor數量，減低效果。

### 傳導結束
-  神經傳導素需快速失效，否則受體會失敏(Desensitization)
-  神經傳導素由軸突末稍的「轉運子」回收，進入神經末稍或神經膠細胞中。
-  神經傳導素分解 (Enzymatic Deactivation):
    -  如分解乙醯膽鹼之酵素 Acetylcholinesterase (AChE)。

### 神經傳導素的釋放
![](https://i.imgur.com/V7utfsR.jpg)

### 神經迴路Neural Circuit
![](https://i.imgur.com/D9htjyi.png)

-  行為是一群神經活動的結果，達成特定活動之神經群謂之神經迴路
-  最簡單的迴路是膝跳反射 Knee Jerk Reflex，多數的中樞迴路較此複雜
-  視覺訊息的傳遞涉及一連串的神經，成為神經鏈 Neural Chain
-  在神經鏈中，常有匯聚 (Convergence)、發散 (Divergence)的現象;同一層級的神經常有旁側抑制(Lateral Inhibition)的現象出現，使得神經活動更為複雜

## 拾貳、突觸Synapses
- • 種類
    - ➡導電突觸Electrical Synapses
      - 兩個神經元之間相距只有 3 nm，可以透過間隙連接Gap Junction將電 流直接由突觸前的神經元傳到突觸後的神經元。
      - 導電突觸在神經細胞中不常 ，但在神經膠細胞、表 細胞、平滑肌、  肌與肝臟細胞常存在。
      - 在發展中的神經系統常出現，他使得發育中彼此相鄰近的細胞可以共享 相似的電流與化學環境訊號，協調彼此的  與成熟過程。
      - 多半 在無脊椎動物或脊椎動物的逃避反射中，感覺神經到運動神經的 突觸。
    - ➡化學突觸Chemical Synapses具有下列的特性   
        - 單向傳導。
      - 訊號放 。
      - 訊號可逆轉:由興奮變抑制
- • 內部結構
    - ➡ Presynaptic membrane of terminal buttons:
      - 液泡Vesicle:儲存神經傳導物Neurotransmitter之處。
      - Presynaptic dense bar projection:釋放神經傳導質之處。   
      - 粒線體Mitochondria: 需要能量。
      - 活躍區Active zone PSD
      - 突觸間隙Synaptic Cleft:200 Å (20-50 nm)。
    - ➡ Postsynaptic membrane:
      - Postsynaptic Density (PSD):是 種蛋 質緻密專業化附著在突觸後之細胞膜
      - 受體Receptors
      - 核糖體Ribosome:蛋 質突觸體Protein Synthesis


### ✔典型突觸作用

### ✔非典型突觸作用

### ✔突觸後電位整合Postsynaptic Integration
- • 神經傳導素的釋放:具量 性QuantalRelease
- • 產 興奮性EPSP、抑制性IPSP突觸後電位
- • 漸進性的突觸後電位GradedPost-SynapticPotential
- • 突觸後電位的漸弱式被動傳導DecrementalandPassiveConduction • 空間加成作 SpatialSummation
- • 時間加成作 TemporalSummation
- • 活動電位的關鍵點AxonHillock、閾限Threshold


### ✔突觸電位之加成作用Summation
- • 神經細胞本體需要進 統整，統合各 之EPSP和IPSP輸 
- • EPSP和IPSP是依賴被動傳導的
- • 由於這並 全有、全無allornone，容許 的電位相加成 電位

### ✔神經元、突觸結合形成電路:膝跳反射Knee Jerk Reflex

### ✔人類大腦上規模的電流活動
- •  前量測腦波記錄可分為兩種 
    - ➡腦電波Electroencephalogram, EEG
      -    測量 腦 質的電流
      - 發 在細胞外的電流，是由細胞群與其他細胞群之間的電位差形成的   
      - 記錄腦中成千上萬神經元活動的結果
    - ➡腦磁波Magnetoencephalographic, MEG
      - 此乃根據法拉第定律─電 磁
      - 當腦神經活化時所產 的電訊號會引發磁場變化，所偵測到訊號的 即為腦磁波
- • 頭 電極在使  種叫做電腦描記器(electroencephalograph)的機器
    - ➡ 來記錄腦電波圖 (EEG) 的
- • ERP的全名為Event-RelatedPotential，即為「事件關聯的電位波」
    - ➡指在將EEG訊號以刺激Stimulus、 發動作Eevent或反應Response為基點，取固定的時間間距
- • Auditory-evokedbrainstempotentials腦幹聽覺誘發電位

## 拾參、受體Receptor
- • 受體興奮 
    - ➡神經傳導素與突觸後樹突或細胞本體細胞膜上的受體結合。
      - 導致突觸後細胞膜上的某些離 管道打開:化學控制管道Chemical- Gated channel
      - 導致突觸後細胞膜快速的電位變化➡突觸後電位Postsynaptic Potential(PSP)
      - 化學控制管道和電位控制管道不同，不會擴及開放附近的管道。
      - 突觸後電位以電流 式在細胞膜上流動，隨距離 逐漸衰退。
      - 對照動作電位不隨距離 衰退。
- • 離 型受體IonotropicReceptors:直接 
    - ➡興奮性離 受體Excitatory Ionotropic Receptors
      - 離 受體本 即是 個離 管道
       - 醯膽鹼 Acetylcholine(ACh) 、麩胺酸Glutamine
      - ACh分 和ACh受體結合，打開管道，容許 Na+/K+ 通過➡產 興奮性突觸後電位 (excitatory post synaptic potentials, EPSP) ➡突觸後細胞膜電位到達鈉與鉀平衡電位的加權平均值。
    - ➡抑制性離 受體Inhibitory Ionotropic Receptors
       - 胺酸 (glycine) 與GABA會使神經元更難興奮
      - 打開K+ 管道 (平衡電位 -80 mV)，可造成IPSP。
      - 打開Cl-的管道，則會使得細胞膜鉗定在Cl-的平衡電位 ( -65 mV)。
- • 代謝型受體 Metabotropic Receptor(GPCR):間接
    - ➡ G protein: 嘌呤核苷酸結合蛋 guanosine-nucleotide binding protein 原本與 GDP結合，當神經傳導素與受體結合後，GTP取代GDP，會興 奮此 蛋 質。
    - ➡ G蛋 受刺激後產 慢速突觸後電位:
      - 啟動的G蛋 、再啟動細胞內的效應器—即第 傳訊者
      - G蛋 或第 傳訊者透過對離 管道/其他機制改變突觸後膜電位。
      - ACh作 於 肌上，便會透過muscarinic metabotropic ACh receptors打開鉀離 管道，然後造成過極化，造成細胞的電位降低，肌收縮減少。 
     - ➡第 傳訊者會改變細胞內代謝功能。
- •   型受體Autoreceptor 
    - ➡  受體是位於突觸前神經細胞終端上的受體，並且 作信號轉導中的反饋 環的 部分。
    - ➡  型受體是對  所分泌的神經傳導素有反應的受體。 在樹突，細胞本體及軸突末稍均可能存在。 
    - ➡多半是代謝型受體，對  所分泌的神經傳導素有反應。 
    - ➡控制神經活動的安全閥:
      - 抑制本 神經傳導素合成速率。   
      - 降低神經傳導素釋放速率。
      - 壓抑神經活動頻率。

### ✔受體興奮

### ✔離子型受體、代謝型受體

### ✔乙醯膽鹹受體Acetylcholine (ACh) Receptor

## 拾肆、其他補充 
### ✔光遺傳學技術Optogenetics

### ✔神經肌肉聯會Neuromuscular junction
- •  常快速且有效率。
- • 肌 上的突觸後肌膜可以稱之為motorendplate(肌終板)
    - ➡可收集所有釋放的神經傳導素。
- • 保證神經對肌 的控制必然不出差錯。
- • 神經肌 聯會後部:充斥肌 細胞膜內的 醯膽鹼受體通道(acetylcholinereceptor，AChR)
- • 神經末梢釋放的ACh和肌 的AChR通道結合
    - ➡引起 量離 的流動，以及局部膜的去極化，隨即引發肌 的動作電位，導致收縮。

### ✔AChR 與蛇毒大師李鎮源
- • 各種離 通道中，以AChR通道的功能和分 結構的研究最為透澈。
- • 主要的原因在於產於台灣本島的 傘節蛇毒(α-bungarotoxin,略寫α-BTX)的特殊性質。
- • 發現α-BTX專攻神經肌 連會的AChR通道，阻 其作 
- •  者之間親和性極 ， 旦結合之後便不再分離，正 以解釋此蛇毒的劇烈毒性。
- • α-BTX的特性正好 來追蹤「AChR的分 」在 化分離時， 得確認純化出來的AChR通道分 。
- • 此蛇毒對AChR通道功能的探討功不可滅，並追蹤此通道在細胞內的發 、調節及在神經肌 交互作 之中擔任的  。
- • 由 傘節Bungarusmulticinitus蛇毒中純化出來的毒素α-bungarotoxin(神經連接後毒素postsynaptic toxin)，被證實作 於突觸後肌終板部位，會抑制運動神經-肌 的傳遞。
- • 找到另 種毒素β-bungarotoxin(神經連接前毒素presynaptictoxin)，作 於突觸前運動神經末梢，阻  醯膽鹼的釋放，產 不可逆性的神經- 肌傳導阻斷作 。 

### ✔癲癇症Seizure Disorders
- • 癲癇Epilepsy:俗稱「 癲瘋」或稱「豬 癲」。
- • 癲癇是因為腦部神經細胞過度活躍(即漏電) 引起的臨床表現，是 規模神經細胞同時興奮所致使腦部電位混亂。
- • 發 率:在 般的流 病學上之探討發現有0.3%~1%的  患有癲癇。
- • 癲癇Epilepsy:
    - ➡定義上它是 種神經性疾病的症狀，算是 種 理狀態 
    - ➡起因:腦細胞 時性的過度放電所引起 
    - ➡發作原因不明，且會重複發 ，故患者需 期服 抗癲癇藥物 
    - ➡若每次發作都有特殊或特定因素 (如發燒、喝酒、藥物等) 才發 ，雖是 次 的癲癇發作，僅以『癲癇症』(seizure) 稱之

## 拾伍、例外
- • 不是所有的神經元均有軸突並傳遞活動電位。
- • 不是所有的神經突觸均產 在axon與dendrites或soma之間。
- • 每 種神經末稍可能有不只 種神經傳導素。
- •  種神經傳導素可以產 EPSP或IPSP。
- • 每 種神經傳導素不只 種受體。
- • 不是每 個synapse均依賴化學傳導。Gap junction的存在
- • 存在有雙向傳遞的突觸。
- • 神經元不是有input 來才活動，沒有input便  死寂。
- • EPSP，IPSP未必代表behavioral activation或deactivation





## 相關人物
美國的生理學家Kenneth C. Cole發明了Voltage Clamp的技術，
可以將電位利用負回饋的方式泊於某一個定點。
2. 英國的生理學家Alan Hodgkin & Andrew Huxley利用這個技術
將膜電位定於不同的電位點上（亦即將Vm定泊在從- 80 mV到
+50 mV的任何一點），因此得以研究在該電位點上離子的行
為表現。
– Giant axon of the squid (直徑0.5 mm)。
– 活動電位是由流入細胞的鈉離子（Na+）造成的。
– At the peak, Nernst equation: +40 mV。
– In the resting state:由鉀離子 (K+) 負責調控。
– Nobel Prize in 1963。


Roderick MacKinnon: 2003 Nobel
Prize in Chemistry:
– M.D.: 心跳頻率與神經衝動。
– In 1998, this self-taught x-ray
crystallographer produced the
first high-resolution 3-D image
of the voltage-gated K+
channel structure。

Cajal 發現神經受損後，退化不會無限制擴展至整個系統。
• Sherrington (1897) 以下列之證據顯示神經與神經間的聯繫非直接而提出突
觸存在的看法：
– 延宕作用：0.5 – 2 msec 。
– 時間加成作用：先後以閾下值刺激同一地方可以引起反射。
– 空間加成作用：同時以閾下值刺激幾個不同的地方可以引起反射。
– 反向作用：同一次刺激，興奮某些肌肉抑制另一些肌肉，刺激狗的一
隻腳，該隻腳會收縮，另三腳會撐直。 EPSP vs. IPSP。
• 生物學家奧圖‧羅威 (Otto Loewi, 1921) 發現青蛙心臟的迷走神經是用化學
物質在傳遞。他稱此物質為vagusstoff，後來證實是乙醯膽鹼acetylcholine。
• Fushpan & Potter (1959) 證實 electrical synapses 存在。
• Palay 在電子顯微鏡下看到確實兩個神經相接處有縫隙存在。
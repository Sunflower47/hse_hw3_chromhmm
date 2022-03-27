# hse_hw3_chromhmm
Ссылка на Google Colab: https://colab.research.google.com/drive/1o_-kBDEEIsZExNbR07doXed4v9F1pYLJ?usp=sharing
# Часть 1
Клеточная линия из в Дз2 (NT2/D1) не содержит достаточно ChIP-seq экспериментов в рассматриваемых гистоновых метках.

![image](https://user-images.githubusercontent.com/71615626/160298985-725d991e-0753-4454-b495-7b6a667ccadb.png)
Вместо нее была взята NHEK.
# Гистоновые метки

|Гистоновая метка|                           Имя файла                                 |
:--------------:|:------------------------------------------------------------:
H3K27ac         |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k27acStdAlnRep1.bam 
H3K27me3        |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k27me3StdAlnRep1.bam
H3K36me3        |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k36me3StdAlnRep1.bam
H3k4me1         |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k4me1StdAlnRep1.bam 
H3K4me2         |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k4me2StdAlnRep1.bam 
H3k4me3         |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k4me3StdAlnRep1.bam 
H3K79me2        |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k79me2AlnRep1.bam   
H3K9ac          |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k9acStdAlnRep1.bam  
H3K9me1         |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH3k9me1StdAlnRep1.bam 
H4k20me1        |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekH4k20me1StdAlnRep1.bam
NhekControl     |  wgEncodeBroadHistone/wgEncodeBroadHistoneNhekControlStdAlnRep1.bam

# ChromHMM

![image](https://user-images.githubusercontent.com/71615626/160304014-89cae02c-0fba-493e-a11a-66df4c300ada.png)

![image](https://user-images.githubusercontent.com/71615626/160304060-a41ee84d-46ac-4e8b-8208-84c07aa02eab.png)

![image](https://user-images.githubusercontent.com/71615626/160304083-0852086b-fc42-47cd-9d3c-00f28e963f12.png)

![image](https://user-images.githubusercontent.com/71615626/160304095-1530c6f4-0eb4-4e57-be36-0232774d59a0.png)

![image](https://user-images.githubusercontent.com/71615626/160304168-68b0997d-c11c-484a-972a-ff90f8353774.png)

# Обозначения эпигенетических типов

![image](https://user-images.githubusercontent.com/71615626/160304863-b8c1efa5-bd30-45a1-8ff1-b95a631346ec.png)

Подает на участок репрессированного гетерохроматима. Ассоциировано с Genome, laminB1lads.

![image](https://user-images.githubusercontent.com/71615626/160305076-7ec97606-7227-4c91-abc8-7c7159f729cd.png)

Подает на участок репрессированного гетерохроматима. Ассоциировано с laminB1lads, RefSeqTES, RefSeqExon

![image](https://user-images.githubusercontent.com/71615626/160305116-81218260-5dc9-4825-a35e-6494991bd504.png)

Данное состояние попадает на интрон. Ассоциировано с CpGIsland, RefSeqTSS, RefSeqExon, RefSeqTSS2kb, RefSeqTES

![image](https://user-images.githubusercontent.com/71615626/160305166-030f2a7a-47cd-4576-9abb-09f222d325db.png)
Данное состояние попадает на интрон.
Асоциировано с CpGIsland, RefSeqExon, RefSeqTSS, RefSeqTSS2kb, RefSeqTES

![image](https://user-images.githubusercontent.com/71615626/160305295-1e59cb4c-e7df-46cd-ac3a-e52afef99594.png)

Это состояние нe попало на ген.Ассоциировано с RefSeqTES, laminB1lads.

![image](https://user-images.githubusercontent.com/71615626/160305438-b3f405b0-5b88-48fc-94d6-243999b941a1.png)

Данное состояние нe попало на ген или могло попасть на интрон. Ассоциировано с laminB1lads, RefSeqTES

![image](https://user-images.githubusercontent.com/71615626/160305468-f6620bec-2ced-4125-9769-0610b6095437.png)

Данное состояние попадает на интрон. Ассоциировано с RefSeqGene, RefSeqTES

![image](https://user-images.githubusercontent.com/71615626/160305518-37cd9b2d-8d36-48fe-96e2-df62c8d5a158.png)

Данное состояние попадает на интрон. Ассоциировано с RefSeqGene.

![image](https://user-images.githubusercontent.com/71615626/160305532-867754da-754f-4294-a682-8f81f95e4def.png)

Попадает транскрибируемый участок гена. Ассоциировано с RefSeqGene

![image](https://user-images.githubusercontent.com/71615626/160305557-4feab824-145e-4b2c-be6e-69d03f02c47e.png)

Попадает транскрибируемый участок гена. Чаще всего ассоциировано с RefSeqExon, RefSeqGene, RefSeqTES

# Часть 2
![image](https://user-images.githubusercontent.com/71615626/160305598-54dc803e-d29d-4d2d-b804-3c56476dae18.png)



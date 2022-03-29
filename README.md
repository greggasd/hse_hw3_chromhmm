# Антонников Григорий, HW3

### Ссылка на Colab (основная и бонусная часть): 
https://colab.research.google.com/drive/1LcHI94nBqIxKLLA5HAdiYwogVDJDQo8_?usp=sharing
### Клеточная линия - HMEC

![Снимок экрана 2022-03-28 в 20 22 21](https://user-images.githubusercontent.com/93208971/160468579-194e0c8c-e742-49fa-88be-1d5cab492cf0.png)

# Основная часть

## Список 10-ти гистоновых меток

| Гистоновая метка | Имя файла | 
| :---: | :---: | 
| H3k27ac | H3k27ac.bam |
| H3k27me3| H3k27me3.bam |
|H3k36me3 | H3k36me3.bam |
|H3k4me1 | H3k4me1.bam |
|H3k4me2 | H3k4me2.bam |
|H3k4me3 | H3k4me3.bam |
|H3k79me2 | H3k79me2.bam |
|H3k9ac | H3k9ac.bam |
|H3k09me3 | H3k09me3.bam |
|H4K20me1 | H4K20me1.bam |

## ChromHMM: картинки из выдачи
| Название | Картинка | 
| :---: | :---: | 
|transitions_10| ![transitions_10](https://user-images.githubusercontent.com/93208971/160502012-51d0b0f5-43f1-410b-980e-9370fcea15e4.png)|
|emissions_10| ![emissions_10](https://user-images.githubusercontent.com/93208971/160501973-30db0046-58d5-4351-b8bd-4f348a6c37e9.png)|
|Hmec_10_overlap|![Hmec_10_overlap](https://user-images.githubusercontent.com/93208971/160501992-73f7044a-4944-420f-82c6-fa9be9dd7433.png)|
|Hmec_10_RefSeqTES_neighborhood|![Hmec_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/93208971/160502061-2e98d87c-93ad-4d94-be67-ce988ec855e8.png)|
|Hmec_10_RefSeqTSS_neighborhood|![Hmec_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/93208971/160502092-4b089692-19db-4672-b15e-b57ed596107f.png)|
## UCSC GenomeBrowser
### Настройки:
![Снимок экрана 2022-03-29 в 19 45 02](https://user-images.githubusercontent.com/93208971/160663494-8a68a805-d2a3-4e1b-a895-abcd1185ec7f.png)
### Результаты(на примере state 5,7,8):
 | State	 | Картинка genome.ucsc  |
 | :---: | :---: | 
| 5 |![image](https://user-images.githubusercontent.com/93208971/160666253-5a569486-5120-4e84-8ce9-01cba29da0aa.png)|
| 7 |![image](https://user-images.githubusercontent.com/93208971/160665769-c0f64c64-9a01-4312-82cc-a5faa17bb5c5.png)| 
| 9 |![image](https://user-images.githubusercontent.com/93208971/160665167-38154442-6fb7-4cea-9185-fe1d21125b3d.png)|


## Табличка с номерами типов, их характерные метки и присвоенные им названия

 | State	 | Характерные гистоновые метки | Название эпигенетического типа |
 | :---: | :---: | :---: | 
 | 1| H3K4me1 ,H3K4me2, H2AFZ, H3K4me3, H3K9ac, H3K27ac, H3K79me2 |1_Insulator|
 | 2| H3K4me1, H3K4me2, H2AFZ, H3K4me3, H3K27ac |2_WeekPromoter|
 | 3| H3K4me1 ,H3K4me2, H2AFZ, H3K9ac, H3K27ac |3_WeekTransckribet|
 | 4| H3K4me1, H3K4me2, H3K27ac |4_PoisedPromoter|
 | 5| H3K4me1 ,H3K4me2, H3K4me3, H3K27ac, H3K79me2, H3K36me3 |5_TranskriptionalTransation|
 | 6| H3K79me2, H3K36me3 |6_TranskriptionalЕlongation|
 | 7| H3K36me3| 7_ActivePromoter|
 | 8| H3K9me3 |8_StrongЕnhancer|
 | 9| - - - |9_PoisedЕnhancer|
 | 10|  H3K27me3 |10_Heterochromatin/lo|
 
 
# Бонусная часть
Новый файл "Hmec_10_dense_new" в репозитории
### Результаты на нескольких примерах 

![image](https://user-images.githubusercontent.com/93208971/160693364-dbc54635-4eb0-411f-81ad-fc7eb71a7d06.png)
![image](https://user-images.githubusercontent.com/93208971/160693458-c71d9b2e-34bf-4bd9-8684-9ed82a7ba591.png)


 | :---: | :---: | :---: | 

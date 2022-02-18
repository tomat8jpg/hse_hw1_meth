# hse_hw1_meth
коллаб - https://colab.research.google.com/drive/1MkUlzPjIQtuRkC45NpnTB9B9VXgZ40RU?usp=sharing
# Анализ QC прочтений
Отчет FastQC для стадии бластоцисты, анализ внутренней клеточной массы - file:///C:/Users/taran/Desktop/SRR5836475_1_fastqc.html
Какие особенности можно наблюдать по сравнению с секвенированием ДНК или РНК? Для изучения метилирования используется секвенирование с бисульфитной конверсией, при котором неметилированные цитозины превращаются в урацил (на сиквенсе выглядит как тимин). Для обычного ДНК/РНК секвенирования содержание каждого нуклеотида примерно одинаково. В нашем случае можно наблюдать аномально высокое количество тимина и низкое цитозина, что возникает из-за пробоподготовки образцов.  
![image](https://user-images.githubusercontent.com/60805733/154717616-3a360ec6-94b4-4895-9192-8ec6e403d492.png)  
При исследовании графика GC-состава можно заметить двугорбое распределение (в отличие от нормального для ДНК сиквенсов) и пониженное содержание GC-нуклеотидов. Это также объясняется методикой подготовки образцов для секвенирования. 
![image](https://user-images.githubusercontent.com/60805733/154717638-356b249e-348b-4b58-80ed-648d3ac756cc.png)  
# Выравнивание ридов на 11 хромосому мыши
| Стадия | Номер | 11347700-11367700 | 40185800-40195800 |
| :---: | :---: | :---: | :---: |
| 8Cell | SRR5836473 | 1090 | 464 |
| ICM | SRR5836475 | 1456 | 630 |
| Epiblast | SRR3824222 | 2328 | 1062 |
# количество дуплицированных прочтений
| Стадия | Номер | %duplicated | Отчет |
| :---: | :---: | :---: | :---: |
| 8Cell | SRR5836473 | 18.31 | [8cell.html](https://github.com/tomat8jpg/hse_hw1_meth/blob/main/data/SRR5836473_1_bismark_bt2_PE_report.html) |
| ICM | SRR5836475 | 9.08 | [icm.html](https://github.com/tomat8jpg/hse_hw1_meth/blob/main/data/SRR5836475_1_bismark_bt2_PE_report.html) |
| Epiblast | SRR3824222 | 2.92 | [epibl.html](https://github.com/tomat8jpg/hse_hw1_meth/blob/main/data/SRR3824222_1_bismark_bt2_PE_report.html) |
# M-bias plots 
Уровень метилирование эпибласта самый высокий. Самый маленький процент метилирования для образца ICM. Это согласуется с литературными данными  
# 8cell
![image](https://user-images.githubusercontent.com/60805733/154717879-00a76f7c-7333-4454-9b22-ff731b9092c9.png)  
# ICM
![image](https://user-images.githubusercontent.com/60805733/154717936-b0aa98d9-b3e2-4718-a7a5-9701fbac79a7.png)  
# Epiblast
![image](https://user-images.githubusercontent.com/60805733/154718003-feab7db8-dc7e-4061-9f93-6d0bccb28ac0.png)  
# Распределение метилирования
![image](https://user-images.githubusercontent.com/60805733/154718107-1484173f-f8df-41e8-b6e3-7ad29c5b1b8e.png)  
![image](https://user-images.githubusercontent.com/60805733/154718149-1fb0bd8a-8550-47a6-8576-0af8d30adbe3.png)  
![image](https://user-images.githubusercontent.com/60805733/154718196-2fe3880a-5831-4deb-b1b1-5ed544722885.png)  
# Графики уровня метилирования и покрытия для каждого образца
# metilation

# coverage


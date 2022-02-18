# hse_hw1_meth
коллаб - https://colab.research.google.com/drive/1MkUlzPjIQtuRkC45NpnTB9B9VXgZ40RU?usp=sharing
# Анализ QC прочтений
Отчет FastQC для стадии бластоцисты, анализ внутренней клеточной массы - file:///C:/Users/taran/Desktop/SRR5836475_1_fastqc.html
Какие особенности можно наблюдать по сравнению с секвенированием ДНК или РНК? Для изучения метилирования используется секвенирование с бисульфитной конверсией, при котором неметилированные цитозины превращаются в урацил (на сиквенсе выглядит как тимин). Для обычного ДНК/РНК секвенирования содержание каждого нуклеотида примерно одинаково. В нашем случае можно наблюдать аномально высокое количество тимина и низкое цитозина, что возникает из-за пробоподготовки образцов.  
При исследовании графика GC-состава можно заметить двугорбое распределение (в отличие от нормального для ДНК сиквенсов) и пониженное содержание GC-нуклеотидов. Это также объясняется методикой подготовки образцов для секвенирования. 
# Выравнивание ридов на 11 хромосому мыши
| Стадия | Номер | 11347700-11367700 | 40185800-40195800 |
| :---: | :---: | :---: | :---: |
| 8Cell | SRR5836473 | 1090 | 464 |
| ICM | SRR5836475 | 1456 | 630 |
| Epiblast | SRR3824222 | 2328 | 1062 |
# количество дуплицированных прочтений
| Стадия | Номер | %duplicated | Отчет |
| :---: | :---: | :---: | :---: |
| 8Cell | SRR5836473 | 18.31 | [8cell.html](file:///C:/Users/taran/Downloads/SRR5836473_1_bismark_bt2_PE_report.html) |
| ICM | SRR5836475 | 9.08 | [icm.html](file:///C:/Users/taran/Downloads/SRR5836475_1_bismark_bt2_PE_report.html) |
| Epiblast | SRR3824222 | 2.92 | [epibl.html](file:///C:/Users/taran/Downloads/SRR3824222_1_bismark_bt2_PE_report%20(1).html) |
# M-bias plots 
Уровень метилирование эпибласта самый высокий. Самый маленький процент метилирования для образца ICM. Это согласуется с литературными данными  
> 8cell

>ICM

>Epiblast

# Распределение метилирования

# Графики уровня метилирования и покрытия для каждого образца
>metilation

>coverage


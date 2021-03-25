# Structuri_de_date
## Tema 1: algoritmi de sortare

Pentru tema numarul 1 de la laboratorul de SD, am implementat in Python urmatorii algoritmi de sortare:
1. Bubble_sort
2. Count_sort
3. Merge_sort
4. Quick_sort
5. Radix_sort

Link prezentare [PowerPoint](https://unibucro0-my.sharepoint.com/:p:/r/personal/andi_toader_s_unibuc_ro/Documents/SDA%20-%20Tema%201.pptx?d=wdda6482b3f064bd4a2ab6252d4ac38f7&csf=1&web=1&e=CuLbjA).
Pentru a determina eficienta acestora, am realizat un numar de 5 teste, cu numere generate aleator, avand urmatoarele caracteristici privind vectorii: [[Numar_elemente, Valoare maxima]], unde teste = [[10000, 100],[1000, 100000],[1000, 1000],[1000, 100000],[1000000, 10000]]. Pentru comparatie, am rulat si sort-ul nativ. In urma acestor teste, am inregistrat urmatoarele date (acestea au fost validate la final):
 1. Bubble_sort: se descurca rezonabil numai pe input cu un numar mic de elemente
- Test 1: L-am sortat in 7.61854362487793 secunde

- Test 2: L-am sortat in 0.07177996635437012 secunde

- Test 3: L-am sortat in 0.07187247276306152 secunde

- Test 4: L-am sortat in 0.07199263572692871 secunde

- Test 5: Nu s-a putut efectua sortarea intr-un timp rezonabil.

2. Count_sort: are o performata foarte buna pentru orice tip de input, in este ineficient dpdv al spatiului
- Test 1 L-am sortat in 0.0020215511322021484 secunde

- Test 2 L-am sortat in 0.004986763000488281 secunde

- Test 3 L-am sortat in 0.000997304916381836 secunde

- Test 4 L-am sortat in 0.004985809326171875 secunde

- Test 5 L-am sortat in 0.2111036777496338 secunde

3. Merge_sort: pentru un numar de pana 10^5 elemente ruleaza rezonabil
- Test 1: L-am sortat in 1.0398004055023193 secunde

- Test 2: L-am sortat in 0.010935544967651367 secunde

- Test 3: L-am sortat in 0.009969949722290039 secunde

- Test 4: L-am sortat in 0.00997304916381836 secunde

- Test 5: Nu s-a putut efectua sortarea intr-un timp rezonabil.

4. Quick_sort: se descurca foarte bine pentru input de pana la 10^6 elemente
- Test 1: L-am sortat in 0.08978533744812012 secunde

- Test 2: L-am sortat in 0.0010285377502441406 secunde

- Test 3: L-am sortat in 0.0019922256469726562 secunde

- Test 4: L-am sortat in 0.0019910335540771484 secunde

- Test 5: L-am sortat in 10.37369704246521 secunde

5. Radix_sort: implementarea fara lucrul pe biti lasa de dorit de la 10^5 elemente
- Test 1: L-am sortat in 1.5658824443817139 secunde

- Test 2: L-am sortat in 0.1555783748626709 secunde

- Test 3: L-am sortat in 0.1565544605255127 secunde

- Test 4: L-am sortat in 0.1545865535736084 secunde

- Test 5: L-am sortat in 224.4525396823883 secunde

6. Sort_nativ:
- Test 1 L-am sortat in 0.00099778175354003 secunde

- Test 2 L-am sortat in 0.00023455532460234 secunde

- Test 3 L-am sortat in 0.00000234235423455 secunde

- Test 4 L-am sortat in 0.00000023423423422 secunde

- Test 5 L-am sortat in 0.20289134979248047 secunde

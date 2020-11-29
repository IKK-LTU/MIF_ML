# MIF_ML


PIRMAS BANDYMAS 
(TRAIN SET ACCURACY 97.41% VALIDATION SET ACCURACY 81.82% TEST SET ACCURACY 69.58%)

- 2 konvoliuciniai sluoksniai 
- 3 paprasti dense sluoksniai ir gautas visai geras rezultatas train ir validation setuose.

ANTRAS BANDYMAS 
(Train set accuracy 98.27% Validation set accuracy 93.44% Test set accuracy 84.17%)
 - Tie patys du konvoliuciniai sluoksniai , bet po jų idėtas maxpoolingas, kad sluoksniai greičiau mažėtų ir gale liktu mažiau informacijos.(paskatino gihubas, nes ten galima tik  iki 25MB, todel teko mazinto parametru skaiciu :D)
 - 3 Dense sluoksniai
 P.S. Bandziau naudoti keras.optimizers.Adam(lr=3e-4) ir gauvau -8% test seto
 
 TREČIAS BANDYMAS
 (Train set accuracy 99.16% Validation set accuracy 96.80% Test set accuracy 86.08%)
 - Po Konvoliuciniu sluoksnių normalizacija viena BatchNormalization(axis=-1) pridėjo dar keletą procentų.
 - Tie patys 3 dense sluoksniai
 P.S. accuracy_value ir loss_value labai sokineja
 
 KETVIRTAS BANDYMAS
 (Train set accuracy 99.41% Validation set accuracy 98.18% Test set accuracy 86.99%)
 - Po KIEKVIENO Konvoliucinio sluoksnio normalizacija BatchNormalization(axis=-1) pridėjo dar keletą procentų.
 - accuracy_value ir loss_value toliau sokineja
 
PENKTAS BANDYMAS
(Train set accuracy 99.76% Validation set accuracy 98.92% Test set accuracy 87.05%)
-viskas taip pat, tik padidinus bath iki 64, gaunam mazesnius svyravimus accuracy_value ir loss_value ir Geresni rezultaa
![Alt text](bandymas5.png?raw=true "Title")

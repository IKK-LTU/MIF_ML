# MIF_ML


PIRMAS BANDYMAS 
(TRAIN SET ACCURACY 97.41% VALIDATION SET ACCURACY 81.82% TEST SET ACCURACY 69.58%)

- Du konvoliuciniai sluoksniai 
- Du paprasti dense sluoksniai ir gautas visai geras rezultatas train ir validation setuose.

ANTRAS BANDYMAS 
(Train set accuracy 98.27% Validation set accuracy 93.44% Test set accuracy 84.17%)
 - Tie patys du konvoliuciniai sluoksniai , bet po jų idėtas maxpoolingas, kad sluoksniai greičiau mažėtų ir gale liktu mažiau informacijos.(paskatino gihubas, nes ten galima tik  iki 25MB, todel teko mazinto parametru skaiciu :D)
 - 2 Dense sluoksniai
 P.S. Bandziau naudoti keras.optimizers.Adam(lr=3e-4) ir gauvau -8% test seto
 
 

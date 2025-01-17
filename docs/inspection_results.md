**Experiment1**

normality test: D'Agostino's K-squared test
homoscedasticity test: Levene test
test: Kruskal-Wallis test
posthoc test: Dunn test

```
Reevaluated normality test for intro: Statistics = 6.77703334129838, p-value = 0.03375871507176448
Reevaluated normality test for drop: Statistics = 12.219343234183503, p-value = 0.00222128012347214
Reevaluated normality test for break: Statistics = 23.83692835909924, p-value = 6.666175974917747e-06
Reevaluated normality test for outro: Statistics = 47.15310321788657, p-value = 5.7654569535665786e-11

Levene's test for homoscedasticity: Statistics = 41.14565669666013, p-value = 1.2188188360901619e-24

Kruskal-Wallis test: Statistics = 70.71760398337165, p-value = 2.996313371181593e-15

Dunn's test results (p-values):
              break      drop         intro         outro
break  1.000000e+00  0.033925  3.378913e-09  1.707324e-13
drop   3.392534e-02  1.000000  2.913576e-03  5.754806e-06
intro  3.378913e-09  0.002914  1.000000e+00  9.867979e-01
outro  1.707324e-13  0.000006  9.867979e-01  1.000000e+00
```

___

**Experiment2**

test: Kruskal-Wallis test
posthoc test: Dunn test

```
Kruskal-Wallis test for bass: Statistics = 21.944235974164485, p-value = 6.699727414612584e-05
Dunn's test results for bass (p-values):
          break      drop     intro     outro
break  1.000000  0.043474  1.000000  0.410187
drop   0.043474  1.000000  0.007523  0.000077
intro  1.000000  0.007523  1.000000  1.000000
outro  0.410187  0.000077  1.000000  1.000000
Kruskal-Wallis test for drums: Statistics = 15.194958854800916, p-value = 0.0016573996210620457
Dunn's test results for drums (p-values):
          break     drop     intro    outro
break  1.000000  0.56782  0.001175  1.00000
drop   0.567820  1.00000  0.205490  1.00000
intro  0.001175  0.20549  1.000000  0.02369
outro  1.000000  1.00000  0.023690  1.00000
Kruskal-Wallis test for other: Statistics = 12.616422142686588, p-value = 0.005544002971718798
Dunn's test results for other (p-values):
          break      drop     intro     outro
break  1.000000  1.000000  0.973029  0.334056
drop   1.000000  1.000000  0.039493  1.000000
intro  0.973029  0.039493  1.000000  0.006943
outro  0.334056  1.000000  0.006943  1.000000
Kruskal-Wallis test for vocals: Statistics = 12.565717138080117, p-value = 0.005676402330660584
Dunn's test results for vocals (p-values):
          break      drop     intro     outro
break  1.000000  1.000000  0.030737  0.061607
drop   1.000000  1.000000  0.098813  0.182189
intro  0.030737  0.098813  1.000000  1.000000
outro  0.061607  0.182189  1.000000  1.000000
```

___

**Experiment1ex**

normality test: D'Agostino's K-squared test
homoscedasticity test: Levene test
test: Kruskal-Wallis test
posthoc test: Dunn test

```
Reevaluated normality test for intro: Statistics = 119.00115289149225, p-value = 1.4428725776257455e-26
Reevaluated normality test for drop: Statistics = 44.858455556571414, p-value = 1.8159761587562757e-10
Reevaluated normality test for break: Statistics = 38.911164281784465, p-value = 3.552614090600625e-09
Reevaluated normality test for outro: Statistics = 156.61343343163216, p-value = 9.813525026728907e-35
Levene's test for homoscedasticity: Statistics = 10.711379337734797, p-value = 6.695070123526783e-07
Kruskal-Wallis test: Statistics = 400.5070567814819, p-value = 1.7191869878089723e-86
Dunn's test results (p-values):
              break          drop         intro         outro
break  1.000000e+00  9.729216e-27  2.875717e-03  3.356466e-15
drop   9.729216e-27  1.000000e+00  1.020427e-46  3.166525e-81
intro  2.875717e-03  1.020427e-46  1.000000e+00  2.264225e-05
outro  3.356466e-15  3.166525e-81  2.264225e-05  1.000000e+00
```

___

**Experiment2ex2**

test: Kruskal-Wallis test
posthoc test: Dunn test

```
Kruskal-Wallis test for bass: Statistics = 377.15480136069164, p-value = 1.9643655616885717e-81
Dunn's test results for bass (p-values):
              break          drop         intro         outro
break  1.000000e+00  6.655353e-15  8.450948e-18  2.344192e-14
drop   6.655353e-15  1.000000e+00  8.127275e-64  3.260026e-57
intro  8.450948e-18  8.127275e-64  1.000000e+00  1.000000e+00
outro  2.344192e-14  3.260026e-57  1.000000e+00  1.000000e+00
Kruskal-Wallis test for drums: Statistics = 285.1885099565866, p-value = 1.5963307835911834e-61
Dunn's test results for drums (p-values):
              break          drop         intro         outro
break  1.000000e+00  1.161313e-43  9.704207e-02  1.000000e+00
drop   1.161313e-43  1.000000e+00  1.442748e-30  6.113751e-49
intro  9.704207e-02  1.442748e-30  1.000000e+00  1.099672e-02
outro  1.000000e+00  6.113751e-49  1.099672e-02  1.000000e+00
Kruskal-Wallis test for other: Statistics = 343.55226926076966, p-value = 3.7133658175848674e-74
Dunn's test results for other (p-values):
              break          drop         intro         outro
break  1.000000e+00  1.000000e+00  6.749514e-39  4.973208e-42
drop   1.000000e+00  1.000000e+00  6.671972e-35  6.789141e-38
intro  6.749514e-39  6.671972e-35  1.000000e+00  1.000000e+00
outro  4.973208e-42  6.789141e-38  1.000000e+00  1.000000e+00
Kruskal-Wallis test for vocals: Statistics = 330.4136558583632, p-value = 2.5963533295436184e-71
Dunn's test results for vocals (p-values):
              break          drop         intro         outro
break  1.000000e+00  6.005825e-01  5.110993e-41  3.186811e-41
drop   6.005825e-01  1.000000e+00  1.147483e-32  7.989889e-33
intro  5.110993e-41  1.147483e-32  1.000000e+00  1.000000e+00
outro  3.186811e-41  7.989889e-33  1.000000e+00  1.000000e+00
```

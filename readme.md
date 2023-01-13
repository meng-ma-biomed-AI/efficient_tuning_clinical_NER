https://arxiv.org/pdf/2210.16771.pdf

## results on 2010 n2c2 gatortron model

### bitfit
- bitfit + ft
```
           precision    recall        f1

strict
  problem     0.9007    0.9076    0.9041
     test     0.8944    0.8898    0.8921
treatment     0.8980    0.8933    0.8956

relax
  problem     0.9562    0.9635    0.9598
     test     0.9460    0.9411    0.9435
treatment     0.9526    0.9477    0.9501


overall
acc: 0.967
strict
              0.8981    0.8982    0.8981

relax
              0.9522    0.9523    0.9523
```

- bitfit reserve + ft
```
          precision    recall        f1

strict
  problem     0.8993    0.9166    0.9079
     test     0.8989    0.8839    0.8913
treatment     0.8892    0.9037    0.8964

relax
  problem     0.9524    0.9707    0.9615
     test     0.9513    0.9355    0.9433
treatment     0.9398    0.9552    0.9475


overall
acc: 0.9668
strict
              0.8961    0.9034    0.8997

relax
              0.9483    0.9560    0.9521
```

- ft
```
           precision    recall        f1

strict
  problem     0.9098    0.9059    0.9078
     test     0.8865    0.8942    0.8903
treatment     0.8990    0.8918    0.8954

relax
  problem     0.9605    0.9565    0.9585
     test     0.9360    0.9441    0.9401
treatment     0.9522    0.9446    0.9484


overall
acc: 0.9669
strict
              0.8998    0.8983    0.8991

relax
              0.9509    0.9494    0.9502
```

- stage ft (5 epoch bitfit then ft)
```
           precision    recall        f1

strict
  problem     0.8901    0.9160    0.9029
     test     0.8977    0.9026    0.9002
treatment     0.8973    0.9006    0.8990

relax
  problem     0.9423    0.9696    0.9558
     test     0.9459    0.9511    0.9485
treatment     0.9488    0.9523    0.9505


overall
acc: 0.9669
strict
              0.8944    0.9075    0.9009

relax
              0.9452    0.9591    0.9521
```


## results on 2010 n2c2 gatortron model

### bitfit
- bitfit + ft
```
bitfit
               precision    recall        f1

strict
   occurrence     0.5702    0.5590    0.5646
         test     0.7727    0.7890    0.7808
      problem     0.7417    0.8157    0.7770
    treatment     0.7750    0.8282    0.8007
clinical_dept     0.6681    0.8361    0.7427
   evidential     0.8229    0.6403    0.7202

relax
   occurrence     0.7151    0.7011    0.7080
         test     0.8868    0.9056    0.8961
      problem     0.8645    0.9508    0.9056
    treatment     0.8762    0.9363    0.9053
clinical_dept     0.7358    0.9208    0.8180
   evidential     0.8229    0.6403    0.7202


overall
acc: 0.8922
strict
                  0.7232    0.7607    0.7415

relax
                  0.8356    0.8789    0.8567
```
```
bitfit + ft
               precision    recall        f1

strict
   occurrence     0.6518    0.5714    0.6090
         test     0.8211    0.8729    0.8462
      problem     0.8465    0.8666    0.8564
    treatment     0.8546    0.8653    0.8600
clinical_dept     0.7183    0.8743    0.7887
   evidential     0.7187    0.7899    0.7526

relax
   occurrence     0.7695    0.6747    0.7190
         test     0.8921    0.9484    0.9194
      problem     0.9259    0.9478    0.9367
    treatment     0.9242    0.9357    0.9299
clinical_dept     0.7542    0.9180    0.8281
   evidential     0.7187    0.7899    0.7526


overall
acc: 0.9136
strict
                  0.7989    0.8101    0.8044

relax
                  0.8740    0.8862    0.8801
```

- bitfit reserve + ft
```
               precision    recall        f1

strict
   occurrence     0.6719    0.5826    0.6241
         test     0.8261    0.8733    0.8491
      problem     0.8280    0.8823    0.8543
    treatment     0.8121    0.8927    0.8505
clinical_dept     0.6341    0.9303    0.7542
   evidential     0.8238    0.6756    0.7424

relax
   occurrence     0.7813    0.6775    0.7257
         test     0.8941    0.9452    0.9189
      problem     0.9009    0.9601    0.9296
    treatment     0.8697    0.9561    0.9109
clinical_dept     0.6667    0.9781    0.7929
   evidential     0.8238    0.6756    0.7424


overall
acc: 0.9106
strict
                  0.7851    0.8218    0.8030

relax
                  0.8533    0.8933    0.8729
```

- ft

```
               precision    recall        f1

strict
   occurrence     0.5952    0.6214    0.6081
         test     0.8323    0.8549    0.8434
      problem     0.8469    0.8666    0.8566
    treatment     0.8706    0.8504    0.8604
clinical_dept     0.7497    0.8306    0.7881
   evidential     0.8263    0.6874    0.7505

relax
   occurrence     0.6961    0.7267    0.7110
         test     0.9112    0.9360    0.9234
      problem     0.9258    0.9473    0.9365
    treatment     0.9376    0.9159    0.9266
clinical_dept     0.7916    0.8770    0.8321
   evidential     0.8283    0.6891    0.7523


overall
acc: 0.9111
strict
                  0.7959    0.8059    0.8009

relax
                  0.8712    0.8822    0.8767
```

- bitfit 5 epoch
```
               precision    recall        f1

strict
   occurrence     0.6079    0.6291    0.6183
         test     0.8544    0.8623    0.8583
      problem     0.8662    0.8744    0.8703
    treatment     0.8689    0.8766    0.8727
clinical_dept     0.6962    0.8798    0.7773
   evidential     0.7849    0.7176    0.7498

relax
   occurrence     0.7104    0.7351    0.7225
         test     0.9256    0.9341    0.9298
      problem     0.9372    0.9462    0.9417
    treatment     0.9287    0.9369    0.9328
clinical_dept     0.7384    0.9331    0.8244
   evidential     0.7849    0.7176    0.7498


overall
acc: 0.9166
strict
                  0.8025    0.8213    0.8118

relax
                  0.8720    0.8925    0.8821
```
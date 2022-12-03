1. Simple Alex  (wd=0.005) random crop, random horizontal flip, epochs
   ------          YES           YES                             500
- Training accuracy:  0.9512
- Accuracy of the on test images :  65.8

2. Simple Alex  (wd=0.005) random crop, random horizontal flip, epochs
   ----          YES            NO                               500       
   - Training accuracy:  0.8946
   - Accuracy of the on test images :  51.0

3. Simple Alex  (wd=0.005) random crop, random horizontal flip, epochs
   ----         NO            NO                               500
   - Training accuracy:  1.0
   - Accuracy of the on test images :  53.7
4. Simple Alex  (wd=0.005) random crop, random horizontal flip, epochs
   ----         NO            YES                               500
   - Training accuracy:  0.9974
   - Accuracy of the on test images :  61.2
5. Simple Alex  (wd=0.005) random crop, random horizontal flip, epochs (RANDOM labels)
   ----         NO            NO                               500
   - Training accuracy:  0.1044
   - Accuracy of the on test images :  8.7
  
6. MLP 1x512  (wd=0.005) random crop, random horizontal flip, epochs
   ----         YES           NO                               500
   - Training accuracy:  1.0
   - Accuracy of the on test images :  43.0

7. MLP 1x512  (wd=0.005) random crop, random horizontal flip, epochs
   ----         NO           NO                               500
   - Training accuracy:  1.0
   - Accuracy of the on test images :  40.2
  
8. MLP 1x512  (wd=0.005) random crop, random horizontal flip, epochs (RANDOM labels)
   ----         NO           NO                                500
   - Training accuracy:  0.0998
   - Accuracy of the on test images :  9.5

9. MLP 3x512  (wd=0.005) random crop, random horizontal flip, epochs
   ----         YES           NO                               500
   - Training accuracy:  1.0
   - Accuracy of the on test images :  40.7
                      
10. MLP 3x512  (wd=0.005) random crop, random horizontal flip, epochs
   ----         NO           NO                               500
   - Training accuracy:  1.0
   - Accuracy of the on test images :  41.4
11. MLP 3x512  (wd=0.005) random crop, random horizontal flip, epochs  (RANDOM labels)
   ----         NO           NO                                500
   - Training accuracy:  0.092
   - Accuracy of the on test images :  10.0
  
## PS
- Simple Alex with wd=0.005 and random crop, random horizontal flip, 100 epochs: (entire dataset)
    Accuracy of the on test images :  69.97
    Training accuracy:  0.7168
- Simple Alex with wd=0.005 and random crop, random horizontal flip, 300 epochs: (entire dataset)
    Accuracy of the on test images :  70.72
    Training accuracy:  0.72676
12. Inception without weight decay  
 --  Accuracy of test  0.32 (epoch = 100)
 --Accuracy of train 0.9999000000000001
15. Inception with weight decay = 0.05 
 --  Accuracy of test  0.34 (epoch = 100)
  --Accuracy of train 1
15. Inception with random lables 
--  Accuracy of test  0.06 (epoch = 100)
. --Accuracy of train 0.14

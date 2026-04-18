# HateSpeechDetection
Hinglish: 29550
Hindi: 8192
English: 24783

these were the count of raw data..we have combined these datasets and balanced the dataset by sampling equal instances from Hinglish, Hindi, and English to avoid language bias during evaluation.


Hinglish distribution:
label
0    15825
1    13725
Name: count, dtype: int64

Hindi distribution:
label
0    4358
1    3834
Name: count, dtype: int64

English distribution:
label
1    20620
0     4163
Name: count, dtype: int64

✅ STEP 1 DONE: Labels cleaned!

RAW DATA:
📊 Hinglish Dataset
Total samples: 29550

Label counts:
label
0    15825
1    13725
Name: count, dtype: int64

Percentage:
label
0    53.55
1    46.45
Name: proportion, dtype: float64

📊 Hindi Dataset
Total samples: 8192

Label counts:
label
0    4358
1    3834
Name: count, dtype: int64

Percentage:
label
0    53.2
1    46.8
Name: proportion, dtype: float64

📊 English Dataset
Total samples: 24783

Label counts:
label
1    20620
0     4163
Name: count, dtype: int64

Percentage:
label
1    83.2
0    16.8
Name: proportion, dtype: float64



combined dataset:


✅ FINAL DISTRIBUTION:
source
hindi       7668
hinglish    7668
english     7668
Name: count, dtype: int64

Label distribution:
label
0    11518
1    11486
Name: count, dtype: int64
Hinglish total samples: 29550
Combined total samples: 23004
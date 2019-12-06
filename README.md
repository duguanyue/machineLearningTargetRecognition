# machineLearningTargetRecognition
Big Homework about charger recognition.
原有的：
train.py
test.py
eval.py
暂时不动，作为参照。

Our Train file：
train_5epoch_for.py

DATA FILE：
ALL：
	data/core_500.txt
	data/coreless_5000.txt
For Train:
	data/train_core_350.txt
	data/train_coreless_3500.txt
For Test:
	data/test_core_150.txt
	data/test_coreless_1500.txt

运行方式（python3）：
python train.py --batch_size 12 --cuda False
（batch_size需要算好了，否则不能整除就报错了）
# m10_kfold
KFold의 옵션 n_splits의 값을 3~10까지 바꾸면서 확인한 상위 3개의 분류모델

# n_splits = 3
1. LinearDiscriminantAnalysis
2. MLPClassifier
3. QuadraticDiscriminantAnalysis
   RadiusNeighborsClassifier
   SVC
# n_splits = 4
1. LinearDiscriminantAnalysis
2. KNeighborsClassifier
3. SVC
# n_splits = 5
1. LinearDiscriminantAnalysis
2. KNeighborsClassifier
3. LabelPropagation
   LabelSpreading
   MLPClassifier
   NuSVC
   QuadraticDiscriminantAnalysis
# n_splits = 6
1. LinearDiscriminantAnalysis 의 정답률=
2. LabelSpreading
   LinearDiscriminantAnalysis
   LinearSVC
   QuadraticDiscriminantAnalysis
   SVC
# n_splits = 7 
1. MLPClassifier
2. SVC
3. LinearDiscriminantAnalysis
# n_splits = 8 
1. LinearDiscriminantAnalysis
2. SVC
3. MLPClassifier
# n_splits = 9
1. LinearDiscriminantAnalysis
2. SVC
3. MLPClassifier
# n_splits = 10
1. LinearDiscriminantAnalysis
2. QuadraticDiscriminantAnalysis
   SVC
3. MLPClassifier
   LabelSpreading
   LabelPropagation
   KNeighborsClassifier
   BaggingClassifier







 


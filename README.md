# Advanced_Machine_Learning_FinalProject_Group6

## Code 파일 목록
* Validation_Oversampling_fv.ipynb
  : Validated Oversampled Dataset을 생성하기 위한 code file 입니다.
  
   input data file: w_red_train.csv
   
   output file: red_50_hidden_221130.pkl (50% hidden 하여 생성한 oversampled dataset)
   
                red_25_hidden_221130.pkl (25% hidden 하여 생성한 oversampled dataset)
                
                red_10_hidden_221130.pkl (10% hidden 하여 생성한 oversampled dataset)
                
                output pickle file은 list 변수를 저장합니다.
                
                저장된 list 변수: [Oversampled dataset with SMOTE(dataframe), Oversampled dataset with ADASYN(dataframe), 
                                  Oversample dataset with SMOTE Tomek(dataframe), Oversampled dataset with Borderline SMOTE(datafrme)]
                                  해당 dataframe 들에는 validation의 결과로 알아낸 closest class가 column으로 추가되어 있습니다.
                
* Datatype1_fv.ipynb
  : Datatype1(Original Dataset)을 평가하기 위한 code file 입니다.
  input data file: w_red_train.csv, w_red_test.csv
* Datatype2_fv.ipynb
  : Datatype2(Original Oversampled Dataset)을 평가하기 위한 code file 입니다.
  input data file: w_red_train.csv, w_red_test.csv
* Datatype3_10hidden.ipynb
  : Datatype3(Validated Oversampled Dataset 10% hidden)을 평가하기 위한 code file 입니다.
  input data file: w_red_train.csv, w_red_test.csv, red_10_hidden_221130.pkl
* Datatype3_25%hidden.ipynb
  : Datatype3(Validated Oversampled Dataset 25% hidden)을 평가하기 위한 code file 입니다.
  input data file: w_red_train.csv, w_red_test.csv, red_25_hidden_221130.pkl
* Datatype3_50%hidden.ipynb
  : Datatype3(Validated Oversampled Dataset 50% hidden)을 평가하기 위한 code file 입니다.
  input data file: w_red_train.csv, w_red_test.csv, red_50_hidden_221130.pkl

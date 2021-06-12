# Merged Data for Korean Emotion Classification 

한국어 감정 분류를 위한 데이터를 혼합  
AI hub 에서 공개하고 있는 감정 데이터를 주로 사용  

AI hub 정책으로 데이터는 미공개 

## Used Data 

한국어_단발성_대화_데이터셋.xlsx : https://aihub.or.kr/keti_data_board/language_intelligence  
한국어_단발성_대화_데이터셋.xlsx : https://aihub.or.kr/keti_data_board/language_intelligence  
감정_분류를_위한_대화_음성_데이터셋_4차.csv : https://aihub.or.kr/keti_data_board/language_intelligence  
감정_분류를_위한_대화_음성_데이터셋_5차.csv : https://aihub.or.kr/keti_data_board/language_intelligence  
~~악플_데이터셋.csv : https://github.com/ZIZUN/korean-malicious-comments-dataset~~  

## Jupyter Notebook explan

EDA.ipynb : 데이터간의 연관성 및 전처리 파악을 위한 EDA 진행  
MergeData.ipynb : 위의 데이터를 혼합하여 감정_분류_데이터셋 생성

## Data preprocessing
감정 분류를 위한 대화 음성 데이터셋의 경우 encoding 문제가 존재  
Aihub 에서 다운받은 (4차_14606,5차_10011) 데이터를 UTF8로 다시 encoding 을 진행 하여  
(감정_분류를_위한_대화_음성_데이터셋_4차.csv, 감정_분류를_위한_대화_음성_데이터셋_5차.csv) 로 Data 에 저장해야 코드 진행 가능
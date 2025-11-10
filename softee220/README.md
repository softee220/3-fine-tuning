# 3-finetuning

### 일반 fine-tuning과 lora 모델 활용 학습의 성능 차이 비교
사용 모델: klue/roberta-base

|항목|일반 파인튜닝|LoRA 파인튜닝|
|---:|---:|---:|
|Validation Accuracy|85.2%|83.1%|
|Training Time|413.87 sec (6.90 min)|165.22 sec (2.75 min)|
|GPU 메모리 사용량|3.37 GB|3.70 GB|
|모델 저장 용량|422.98 MB|4.37 MB|
|etc|

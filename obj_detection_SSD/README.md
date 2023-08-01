# SSD with Pytorch
- 파이토치를 이용해 구현된 SSD모델입니다.

## 데이터 생성
- VOC2012 데이터를 활용합니다.
- make_data.ipynb를 활용합니다.
- 데이터의 용량으로 인해 웹에서 다운합니다.

##  모델 학습
- 데이터 생성 이후 진행합니다.
- SSD_training.ipynb을 활용합니다.
- 아래 링크를 통해 학습된 가중치 파일을 이용할 수 있습니다.
  - https://drive.google.com/drive/folders/1CqzaBx0Z-yCi_x-cOe-KLGK6nacmXT32?usp=sharing

## 추론
- wieghts 폴더에 가중치 파일들이 저장됩니다.
- data폴더 내 이미지를 활용하여 추론이 진행됩니다.
- SSD_inference.ipynb를 활용합니다.

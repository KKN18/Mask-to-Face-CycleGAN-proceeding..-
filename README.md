# Mask-to-Face-CycleGAN (proceeding)

## Environment
모든 작업이 Google Colab Notebooks에서 진행되었습니다.

## Dataset
구글에서 사람 얼굴 사진을 크롤링하여 데이터셋을 구축하였습니다. 

"마스크를 낀 사람"의 사진이 많지 않기 때문에 얼굴에 마스크를 합성하는 소스코드를 이용해 데이터셋을 만들었습니다.

## Problem
현재 데이터셋으로 CycleGAN을 학습시키니 모든 종류의 loss가 일정 수준 이하로 줄어들지 않고 

"마스크"의 특징을 제대로 학습하지 못하는 문제가 발생했습니다.

훨씬 더 많은 데이터셋이 필요한 것으로 보이나 Google Colab Notebooks에서 사용할 수 있는 GPU에 한계가 있기 때문에

추후 개인적으로 GPU를 사용할 수 있을 때까지 잠정 보류할 예정입니다.

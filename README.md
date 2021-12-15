

# 중앙대학교 [공학교육혁신센터] 파이썬 기반 딥러닝 기본 과정


<br>

# 과정 개요

파이썬을 기반으로 하여 딥러닝에 대한 기본적인 사항을 학습합니다.

딥러닝에 대한 개념적인 사항은 이론적인 설명으로 진행하고, 나머지 대부분은 실습으로 진행합니다. 이론적인 내용이라도 수학이나 통계의 사전 지식이 필요없이 이해하고 파악하실 수 있습니다.

실습의 경우 학습자가 코드를 작성하는 것이 아닌 제공되는 데이터와 코드를 사용하여 진행하며, 실 데이터와 실제 동작하는 코드의 실행을 통해 딥러닝이 어떤 코드로 어떻게 학습되어 동작하는 지를 파악합니다. 실습에 사용되는 코드와 작업은 현장 실무에서 사용되는 것으로 이후 딥러닝 심화 과정이나 혹은 딥러닝을 사용한 작업을 진행할 때 직접 사용이 가능합니다.

실습은 구글의 Colab에서 진행하며 일반 PC의 크롬 웹브라우저를 사용하여 진행합니다.

프로그램 경험이 많지 않더라도 또한 데이터 처리나 실무 경험이 없더라도 충분히 딥러닝이 어떤 것이고 활용을 어떻게 할 수 있는 지를 파악할 수 있는 교육입니다.

딥러닝을 이해하고 실제 문제에 적용하여 해결할 수 있다.


<br>

# 교육 목표

- 인공지능과 딥러닝의 개념을 이해합니다.
- 딥러닝의 한계와 장단점을 이해하며 딥러닝으로 할 수 있는 작업을 파악합니다..
- 딥러닝 구현과 학습을 위한 데이터를 이해하고 데이터를 준비하는 방법을 학습합니다.
- 딥러닝 구현을 위한 Keras의 사용법을 학습하고 주요 작업을 실습을 통해 실제 학습과 구현 방법을 학습합니다.


<br>

# 팀프로젝트

[team_project.md](./material/deep_learning/practice_cau_2021/team_project.md)


<br>

# 일자별 계획

## 1일차

- 인공지능 개념 및 동작 원리의 이해 : [deep_learning_intro.pptx](./material/deep_learning/deep_learning_intro.pptx)
    - Perceptron, MLP, DNN 소개
    - DNN의 학습 이해
    - AI, 머신러닝, 딥러닝의 이해
    - 딥러닝 상세 기술 이해

- 흥미로운 딥러닝 결과 : [some_interesting_deep_learning.pptx](./material/deep_learning/some_interesting_deep_learning.pptx)

- 환경
    - colab 사용법
    - python 아주 살짝
    - 기본 linux 명령어 : [linux.md](./material/linux.md), [실습내용](./material/deep_learning/practice_cau_2021/my_first_notebook.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/practice_cau_2021/my_first_notebook.ipynb)


<br>

## 2일차

- Keras로 구현한 딥러닝 : : [dnn_in_keras.ipynb](./material/deep_learning/dnn_in_keras.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_in_keras.ipynb)
    - 표준 Keras 딥러닝 코드
    - 로스 보기
    - 은닉층과 노드 수
    - trian, test 데이터 분리
    - batch size와 학습
    - 데이터 수와 학습
    - 모델 저장과 로딩
    - 학습되지 않는 랜덤 함수
    - Optimizer
    - 다양한 입출력
- callback : [dnn_in_keras_callback.ipynb](./material/deep_learning/dnn_in_keras_callback.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_in_keras_callback.ipynb)
- overfitting 처리 : [dnn_in_keras_overfitting.ipynb](./material/deep_learning/dnn_in_keras_overfitting.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_in_keras_overfitting.ipynb)
- custom data generator : [custom_data_generator.ipynb](./material/deep_learning/custom_data_generator.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/custom_data_generator.ipynb)

- 분류기로서의 DNN
    - 속성 데이터 IRIS 분류 실습 : [dnn_iris_classification.ipynb](./material/deep_learning/dnn_iris_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_iris_classification.ipynb)
<br>

## 3일차

- 영상 데이터의 이해 : [deep_learning_intro.pptx](./material/deep_learning/deep_learning_intro.pptx)

- 영상 분류기로서의 DNN
    - 흑백 영상 데이터 MNIST 분류 실습 : [dnn_mnist.ipynb](./material/deep_learning/dnn_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_mnist.ipynb)
    - 흑백 영상 fashion MNIST 분류 : [dnn_fashion_mnist.ipynb](./material/deep_learning/dnn_fashion_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_fashion_mnist.ipynb)

- 영상 분류기로서의 CNN
    - CNN의 이해 : [deep_learning_intro.pptx](./material/deep_learning/deep_learning_intro.pptx)
    - 흑백 영상 데이터 MNIST 영상분류 : [cnn_mnist.ipynb](./material/deep_learning/cnn_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/cnn_mnist.ipynb)
    - CIFAR10 컬러영상분류 : [cnn_cifar10.ipynb](./material/deep_learning/cnn_cifar10.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/cnn_cifar10.ipynb)

- 전이학습
    [VGG16_classification_and_cumtom_data_training.ipynb](./material/deep_learning/VGG16_classification_and_cumtom_data_training.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/VGG16_classification_and_cumtom_data_training.ipynb)

    - 커스텀 데이터 VGG 데이터 분류 실습 : [flowers.zip](./material/deep_learning/flowers.zip)
        - [practice_custom_image_classification.ipynb](./material/deep_learning/practice_custom_image_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/practice_custom_image_classification.ipynb)
        - [real_practice_glaucoma_classification.ipynb](./material/deep_learning/real_practice_glaucoma_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/real_practice_glaucoma_classification.ipynb)

    
<br>

## 4일차

- RNN
    - text 데이터의 이해 : [deep_learning_intro.pptx](./material/deep_learning/deep_learning_intro.pptx)
    - RNN의 이해 : [deep_learning_intro.pptx](./material/deep_learning//deep_learning_intro.pptx)
    - RNN을 사용한 영화 평가 데이터 IMDB 분류 : [rnn_text_classification.ipynb](./material/deep_learning/rnn_text_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/rnn_text_classification.ipynb)
    - RNN을 사용한 다음 문자 생성 : [rnn_next_character_prediction.ipynb](./material/deep_learning/rnn_next_character_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/rnn_next_character_prediction.ipynb)
    - RNN을 사용한 덧셈 결과 생성 : [seq2seq_addition_using_rnn.ipynb](./material/deep_learning/seq2seq_addition_using_rnn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/seq2seq_addition_using_rnn.ipynb)
    - RNN을 사용한 덧셈 결과 분류 : [rnn_addition_text_classication.ipynb](./material/deep_learning/rnn_addition_text_classication.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/rnn_addition_text_classication.ipynb)     
    - Bert를 사용한 다음 단어 예측 : [next_word_prediction.ipynb](./material/deep_learning/next_word_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/next_word_prediction.ipynb)

- 한글 NLP    
    - RNN을 사용한 한글 영화 평가 데이터 분류 : [korean_word_sequence_classification.ipynb](./material/deep_learning/korean_word_sequence_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_word_sequence_classification.ipynb)
    - Bert를 사용한 한글 영화 평가 데이터 분류 : [korean_word_sequence_classification_with_bert.ipynb](./material/deep_learning/korean_word_sequence_classification_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_word_sequence_classification_with_bert.ipynb)
    - Bert를 사용한 한글 문장 간 관계 분류 : [korean_sentence_relation_classification_with_bert.ipynb](./material/deep_learning/korean_sentence_relation_classification_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_sentence_relation_classification_with_bert.ipynb)
    - Bert를 사용한 한글 문장 간 관계값 예측 : [korean_sentence_relation_regression_with_bert.ipynb](./material/deep_learning/korean_sentence_relation_regression_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_sentence_relation_regression_with_bert.ipynb)
    - Bert를 사용한 한글 문장 간 관계 분류, 커스텀 vocab : [korean_sentence_relation_classification_with_bert_with_custom_vocab.ipynb](./material/deep_learning/korean_sentence_relation_classification_with_bert_with_custom_vocab.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_sentence_relation_classification_with_bert_with_custom_vocab.ipynb)
    - Bert를 사용한 괄호 단어 예측 : [korean_mask_completion_with_bert.ipynb](./material/deep_learning/korean_mask_completion_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_mask_completion_with_bert.ipynb) 

- Keras Functional API  : [functional_api.ipynb](./material/deep_learning/functional_api.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/functional_api.ipynb)

- AutoEncoder
    - AutoEncoder 실습 : [autoencoder.ipynb](./material/deep_learning/autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/autoencoder.ipynb)
    - 디노이징 AutoEncoder : [denoising_autoencoder.ipynb](./material/deep_learning/denoising_autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/denoising_autoencoder.ipynb)
    - Super Resolution : [mnist_super_resolution.ipynb](./material/deep_learning/mnist_super_resolution.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/mnist_super_resolution.ipynb)

- 영상 분할(Segementation)
    - U-Net을 사용한 영상 분할 실습 : [unet_segementation.ipynb](./material/deep_learning/unet_segementation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/unet_segementation.ipynb)
    - M-Net을 사용한 영상 분할 실습 : [mnet_segementation.ipynb](./material/deep_learning/mnet_segementation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/mnet_segementation.ipynb)
    - U-Net을 사용한 컬러 영상 분할 실습 : [unet_segementation_color_image.ipynb](./material/deep_learning/unet_segementation_color_image.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/unet_segementation_color_image.ipynb)

<br>

## 5일차

- 물체 탐지
   - 물체 탐지의 이해
   - YOLO 적용 방법 실습 : [object_detection.md](./material/deep_learning/object_detection.md)
- 강화학습 이해하기 : [deep_learning_intro.pptx](./material/deep_learning//deep_learning_intro.pptx)
- 알파고 이해하기 : [understanding_ahphago.pptx](./material/deep_learning/understanding_ahphago.pptx)

- 얼굴 인식 : [Face_Recognition.ipynb](./material/deep_learning/Face_Recognition.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/Face_Recognition.ipynb)
- 포즈 추출 : [open_pose_using_template.ipynb](material/deep_learning/open_pose_using_template.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/open_pose_using_template.ipynb)
- web cam + colab 실시간 포즈 추출 : [tf_pose_estimation_with_webcam.ipynb](material/deep_learning/tf_pose_estimation_with_webcam.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/tf_pose_estimation_with_webcam.ipynb)
- 영상 데이터 예측 : [cat_with_glasses.ipynb](./material/deep_learning/cat_with_glasses.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/cat_with_glasses.ipynb)


<br>


# 6일차

- 개별 프로젝트 발표

- 질문과 답변


<br>


# 기타

## Template

- 속성 데이터
    - 예측 : [template_attribute_data_regression.ipynb](material/deep_learning/template_attribute_data_regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_attribute_data_regression.ipynb)
    - 분류 : [template_attribute_data_classification.ipynb](material/deep_learning/template_attribute_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_attribute_data_classification.ipynb)
    - 2진 분류 : [template_attribute_data_binary_classification.ipynb](material/deep_learning/template_attribute_data_binary_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_attribute_data_binary_classification.ipynb)    
- 영상 데이터
    - 예측 - vanilla CNN : [template_image_data_vanilla_cnn_regression.ipynb](material/deep_learning/template_image_data_vanilla_cnn_regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_vanilla_cnn_regression.ipynb)
    - 예측 - 전이학습 : [template_image_data_transfer_learning_regression.ipynb](material/deep_learning/template_image_data_transfer_learning_regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_transfer_learning_regression.ipynb)
    - 분류 - vanilla CNN : [template_image_data_vanilla_cnn_classification.ipynb](material/deep_learning/template_image_data_vanilla_cnn_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_vanilla_cnn_classification.ipynb)
    - 분류 - 전이학습 : [template_image_data_transfer_learning_classification.ipynb](material/deep_learning/template_image_data_transfer_learning_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_transfer_learning_classification.ipynb)
    - 2진 분류 - vanilla CNN : [template_image_data_vanilla_cnn_binary_classification.ipynb](material/deep_learning/template_image_data_vanilla_cnn_binary_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_vanilla_cnn_binary_classification.ipynb)
    - 2진 분류 - 전이학습 : [template_image_data_transfer_learning_binary_classification.ipynb](material/deep_learning/template_image_data_transfer_learning_binary_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_image_data_transfer_learning_binary_classification.ipynb)
- 순차열 데이터
    - 숫자열
        - 단일 숫자열 예측 : [template_numeric_sequence_data_prediction.ipynb](material/deep_learning/template_numeric_sequence_data_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_numeric_sequence_data_prediction.ipynb)
        - 단일 숫자열 분류 : [template_numeric_sequence_data_classification.ipynb](material/deep_learning/template_numeric_sequence_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_numeric_sequence_data_classification.ipynb)
        - 다중 숫자열 분류 : [template_multi_numeric_sequence_data_classification.ipynb](material/deep_learning/template_multi_numeric_sequence_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_multi_numeric_sequence_data_classification.ipynb) 
        - 다중 숫자열 다중 예측 : [template_multi_numeric_sequence_data_multi_prediction.ipynb](material/deep_learning/template_multi_numeric_sequence_data_multi_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_multi_numeric_sequence_data_multi_prediction.ipynb)
        - 다중 숫자열 단일 예측 : [template_multi_numeric_sequence_data_one_prediction.ipynb](material/deep_learning/template_multi_numeric_sequence_data_one_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_multi_numeric_sequence_data_one_prediction.ipynb)
    - 문자열
        - 문자열 예측 : [template_text_sequence_data_prediction.ipynb](material/deep_learning/template_text_sequence_data_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_text_sequence_data_prediction.ipynb)
        - 문자열 분류 : [template_text_sequence_data_classification.ipynb](material/deep_learning/template_text_sequence_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_text_sequence_data_classification.ipynb)
        - 문자열 연속 예측 : [template_text_data_sequential_generation.ipynb](material/deep_learning/template_text_data_sequential_generation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_text_data_sequential_generation.ipynb)
    - 단어열
        - 단어열 분류 : [template_word_sequence_data_classification.ipynb](material/deep_learning/template_word_sequence_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_word_sequence_data_classification.ipynb)
        - 단어열 예측 : [template_word_sequence_data_prediction.ipynb](material/deep_learning/template_word_sequence_data_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_word_sequence_data_prediction.ipynb)
        - 한글 단어열 분류 : [template_korean_word_sequence_data_classification.ipynb](material/deep_learning/template_korean_word_sequence_data_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/template_korean_word_sequence_data_classification.ipynb)
        - Bert를 사용한 한글 문장 간 관계 분류 : [korean_sentence_relation_classification_with_bert.ipynb](./material/deep_learning/korean_sentence_relation_classification_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_sentence_relation_classification_with_bert.ipynb)
        - Bert를 사용한 한글 문장 간 관계값 예측 : [korean_sentence_relation_regression_with_bert.ipynb](./material/deep_learning/korean_sentence_relation_regression_with_bert.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/korean_sentence_relation_regression_with_bert.ipynb)


<br>

## 성능 개선

- 성능 개선 개요 : [deep_learning_intro.pptx](./material/deep_learning/deep_learning_intro.pptx)
- 오버피팅 처리 : [dnn_in_keras_overfitting.ipynb](./material/deep_learning/dnn_in_keras_overfitting.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_in_keras_overfitting.ipynb)
- 데이터 수와 성능 : [data_count_and_overfitting.ipynb](./material/deep_learning/data_count_and_overfitting.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/data_count_and_overfitting.ipynb)
- weight 초기화와 성능 : [dnn_in_keras_weight_init.ipynb](./material/deep_learning/dnn_in_keras_weight_init.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/dnn_in_keras_weight_init.ipynb)
- normalization과 성능 : [normalization_and_performance.ipynb](./material/deep_learning/normalization_and_performance.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/normalization_and_performance.ipynb)
- 불균등 데이터 처리 : [treating_imbalanced_data.ipynb](./material/deep_learning/treating_imbalanced_data.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/treating_imbalanced_data.ipynb)
- IMDB 분류에 적용 : [treating_overfitting_with_imdb.ipynb](./material/deep_learning/treating_overfitting_with_imdb.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/treating_overfitting_with_imdb.ipynb)
- MNIST CNN에 callback과 오버피팅 처리 적용 : [boston_house_price_regression.ipynb](./material/deep_learning/boston_house_price_regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/boston_house_price_regression.ipynb)


<br>

## 기타 실습
- 얼굴 인식
    - 얼굴 위치 탐지 실습 : [track_faces_on_video_realtime.ipynb](./material/deep_learning/track_faces_on_video_realtime.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/track_faces_on_video_realtime.ipynb)
    - 얼굴 감정 분류 실습 : [face_emotion_classification.ipynb](./material/deep_learning/face_emotion_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/face_emotion_classification.ipynb)
    
- 영상 데이터
    - 화재 영상 분류 : [fire_scene_classification.ipynb](./material/deep_learning/fire_scene_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/fire_scene_classification.ipynb)    
    - wafer map 영상 분류 : [real_practice_classify_semiconductor_wafermap.ipynb](material/deep_learning/real_practice_classify_semiconductor_wafermap.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/real_practice_classify_semiconductor_wafermap.ipynb)
    - 엔진 블레이드 영상 분류 : [engine_blade_classification.ipynb](material/deep_learning/engine_blade_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/engine_blade_classification.ipynb)

- 속성 데이터
    - 심리설문 데이터 분류 : [real_practice_psychologial_test_classification.ipynb](material/deep_learning/real_practice_psychologial_test_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/real_practice_psychologial_test_classification.ipynb)

- 시계열 데이터
    - 시계열 데이터 처리 : [treating_sequence_data.ipynb](material/deep_learning/treating_sequence_data.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/treating_sequence_data.ipynb)
    - 시계열 데이터 예측 : [wheather_forecasting_using_TimeseriesGenerator.ipynb](material/deep_learning/wheather_forecasting_using_TimeseriesGenerator.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/wheather_forecasting_using_TimeseriesGenerator.ipynb)
    - 시계열 데이터 분류 : [real_practice_classify_semiconductor_time_series_data.ipynb](material/deep_learning/real_practice_classify_semiconductor_time_series_data.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/real_practice_classify_semiconductor_time_series_data.ipynb)

- Dacon 데이터
    - 글자에 숨겨진 MNIST 영상 분류 : [classification_hidden_mnist_in_lettern.ipynb](material/deep_learning/classification_hidden_mnist_in_lettern.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/classification_hidden_mnist_in_lettern.ipynb)
    - 와인 속성 데이타 품질 분류 : [classification_wine_quality.ipynb](material/deep_learning/classification_wine_quality.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/classification_wine_quality.ipynb)

<br>


## How-To

- class_wieght : [howto_class_weight_for_imbalancing.ipynb](./material/deep_learning/howto_class_weight_for_imbalancing.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/howto_class_weight_for_imbalancing.ipynb)


<br>

## GAN

- GAN
    - GAN의 이해 : [deep_learning_intro.pptx](./material/deep_learning//deep_learning_intro.pptx), 
        - 이상탐지 관련 GAN 설명 : [deep_learning_anomaly_detection.pptx](./material/deep_learning/deep_learning_anomaly_detection.pptx)
    - GAN을 사용한 MNIST 학습 실습 : [wgan_gp_mnist.ipynb](./material/deep_learning/wgan_gp_mnist.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/wgan_gp_mnist.ipynb)
    - Conditional GAN의 이해 : [anomaly_detection_using_gan.pptx](./material/deep_learning/anomaly_detection_using_gan.pptx)
    - Cycle GAN의 이해 : [cycle_gan.pdf](./material/deep_learning/cycle_gan.pdf)


## 환경 

- jupyter와 colab 이해 : [jupyter_and_colab.md](./material/env/jupyter_and_colab.md)
- 윈도우 환경에서 linux command HowTo : [how_to_linux_command_on_windows.md](./material/env/how_to_linux_command_on_windows.md)
- Ubuntu 서버 설치하기(다소 오래된) : [2019-10-17_setup_server.pdf](./material/env/2019-10-17_setup_server.pdf)
- GCP에 VM생성하고 Colab 연결하기 : [GCP_VM_and_Colab.pdf](./material/env/GCP_VM_and_Colab.pdf)


<br>

## 기타 자료

- ML Classifiers : [ML_classifiers.ipynb](./material/deep_learning/ML_classifiers.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/ML_classifiers.ipynb)
- DNN regression. boston 집값 예측 : [boston_house_price_regression.ipynb](./material/deep_learning/boston_house_price_regression.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/boston_house_price_regression.ipynb) 
- [의학논문 리뷰](https://docs.google.com/presentation/d/1SZ-m4XVepS94jzXDL8VFMN2dh9s6jaN5fVsNhQ1qwEU/edit)
- GCP에 VM 생성하고 Colab 연결하기 : [create_GCP_VM.pdf](./material/deep_learning/create_GCP_VM.pdf)
- 흥미로운 딥러닝 결과 : [some_interesting_deep_learning.pptx](./material/deep_learning/some_interesting_deep_learning.pptx)
- yolo를 사용한 실시간 불량품 탐지 : https://drive.google.com/file/d/194UpsjG7MyEvWlmJeqfcocD-h-zy_4mR/view?usp=sharing
- YOLO를 사용한 자동차 번호판 탐지 : https://drive.google.com/file/d/1jlKzCaKj5rGRXIhwMXtYtVnx_XLauFiL/view?usp=sharing
- 딥러닝 이상탐지 : [deep_learning_anomaly_detection.pptx](./material/deep_learning/deep_learning_anomaly_detection.pptx)
- GAN을 사용한 생산설비 이상 탐지 : [anomaly_detection_using_gan.pptx](./material/deep_learning/anomaly_detection_using_gan.pptx)
- 이상탐지 동영상 : [drillai_anomaly_detect.mp4](./material/deep_learning/drillai_anomaly_detect.mp4)
- 훌륭한 논문 리스트 : https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap
- online CNN 시각화 자료 : https://poloclub.github.io/cnn-explainer/
- GradCAM : [grad_cam.ipynb](./material/deep_learning/grad_cam.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/grad_cam.ipynb)
- AUC 그리기 :  [draw_auc_with_mnist_cnn.ipynb](./material/deep_learning/draw_auc_with_mnist_cnn.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/cau_2021/blob/master/material/deep_learning/draw_auc_with_mnist_cnn.ipynb)
- 서버 설치 기록 : [2019-10-17_setup_server.pdf](./material/env/2019-10-17_setup_server.pdf)
- GCP에 VM 생성하고 Colab 연결 : [GCP_VM_and_Colab.pdf](./material/env/GCP_VM_and_Colab.pdf)
- TensorFlow 홈 tutorial에서 스타일 변환 : https://www.tensorflow.org/tutorials/generative/style_transfer?hl=ko


<br>

# 교육에 사용된 외부 자료
- dynamic robotics 1 : https://www.youtube.com/watch?v=_sBBaNYex3E
- dynamic robotics 2 : https://www.youtube.com/watch?v=94nnAOZRg8k
- cart pole : https://www.youtube.com/watch?v=XiigTGKZfks
- bidirectional RNN : https://towardsdatascience.com/understanding-bidirectional-rnn-in-pytorch-5bd25a5dd66
- alphago architecture : https://medium.com/applied-data-science/alphago-zero-explained-in-one-diagram-365f5abf67e0
- u-net architecture : https://machinelearningmastery.com/how-to-implement-pix2pix-gan-models-from-scratch-with-keras/
- upsampling : https://kharshit.github.io/blog/2019/02/15/autoencoder-downsampling-and-upsampling
- Denseness architecture : https://hoya012.github.io/blog/DenseNet-Tutorial-1/
- K-fold cross validation : https://m.blog.naver.com/PostView.nhn?blogId=dnjswns2280&logNo=221532535858&proxyReferer=https:%2F%2Fwww.google.com%2F
- M-net architecture : https://hzfu.github.io/proj_glaucoma_fundus.html  
- yolo 적용 예 블로그 : https://nero.devstory.co.kr/post/pj-too-real-03/
- GAN 위조 지폐 : http://mrkim.cloudy.so/board_KBEq62/175378
- GAN paper : https://arxiv.org/pdf/1406.2661.pdf
- Gan paper count : https://blog.naver.com/PostView.nhn?blogId=laonple&logNo=221201915691
- Conditional gan face generation example. https://github.com/Guim3/IcGAN
- Pinpointing example : https://www.geeks3d.com/20180425/nvidia-deep-learning-based-image-inpainting-demo-is-impressive/
- 동영상 스타일 변환 : https://www.youtube.com/watch?v=Khuj4ASldmU
- 얼굴 감정 인식 예 : http://www.astronomer.rocks/news/articleView.html?idxno=86084
- Papers with code : https://paperswithcode.com/
  

<br>


# 딥러닝 활용을 위한 지식 구조

```
Environment
    jupyter
	colab
	usage
		!, %, run
    GCP virtual machine
linux
	ENV
	command
		cd, pwd, ls
		mkdir, rm, cp
		head, more, tail, cat
	util
		apt
		git, wget
		grep, wc, tree
		tar, unrar, unzip
	gpu
		nvidia-smi

python
	env
		python
			interactive
			execute file
		pip
	syntax
        variable
        data
            tuple
            list
            dict
            set
        loop
        if
        comprehensive list
        function
        class
	module
		import

libray
    numpy
        load
        operation
        shape
        slicing
        reshape
        axis + sum, mean
    pandas
        load
        view
	    operation
        to numpy
    seaborn
        charts
    matplot
        plot
        scatter
        hist
        multi draw
        show image

Deep Learning
    DNN
        concept
            layer, node, weight, bias, activation
            cost function
            GD, BP
        data
            x, y
            train, validate, test
            shuffle
        learning curve : accuracy, loss
        tuning
            overfitting, underfitting
            dropout, batch normalization, regularization
            data augmentation
        Transfer Learning
    type
        supervised
        unsupervised
        reinforcement
    model
        CNN
            vanilla, named CNN
        RNN
        GAN
    task
        Classification
        Object Detection
        Generation
	Segmentation
	Pose Extraction
	Noise Removing
	Super Resolution
	Question answering
	Auto Captioning
    data type
    	attribute data
	image data
	natural language data
	time series data

TensorFlow/Keras
    basic frame
        data preparing
            x, y
            train, valid, test
            normalization
            ImageDataGenerator
        fit
        evaluate
        predict
    model
        activation function
        initializer
    tuning
        learning rate
        regularizer
        dropout
        batch normalization
    save/load
    compile
        optimizer
        loss
        metric
```

   

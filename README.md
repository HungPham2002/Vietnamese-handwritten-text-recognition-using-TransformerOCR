<p align="center" dir="auto">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" rel="nofollow">
    <img src="https://camo.githubusercontent.com/29fa0dade8ce1281054a2a4844513e68f8868f15057452c709392fe49b01d398/68747470733a2f2f692e696d6775722e636f6d2f576d4d6e5352742e706e67" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology" data-canonical-src="https://i.imgur.com/WmMnSRt.png" style="max-width: 100%;">
  </a>
</p>
<h1 align="center" tabindex="-1" dir="auto"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><b>CS331.N21.KHCL - THỊ GIÁC MÁY TÍNH NÂNG CAO - ADVANCED COMPUTER VISION </b></h1>

# Information:
- Course: Advanced Computer Vision.
- Course ID: CS331.N21.KHCL
- Lecturer: PhD Mai Tien Dung
- Term: Second term (2022-2023)

# Contact:
<table>
  <thead>
    <tr>
      <th align = "center"> STT </th>
      <th> Name </th>
      <th> Email </th>
      <th> Github </th>
      <th> Linkedin </th>
      <th> Facebook </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align = "center">1</td>
      <td>Pham Huu Hung</td>
      <td>
        <a href = "mailto:20521371@gm.uit.edu.vn">20521371@gm.uit.edu.vn</a>
      </td>
      <td>
        <a href = "https://github.com/HungPham2002">HungPham2002</a>
      </td>
      <td>
        <a href = "https://www.linkedin.com/in/h%C3%B9ng-ph%E1%BA%A1m-h%E1%BB%AFu-488996277/">Hùng Phạm Hữu</a>
      </td>
      <td>
        <a href = "https://www.facebook.com/Hungzt103/" rel = "nofollow">Phạm Hữu Hùng</a>
      </td>
    </tr>
    <tr>
      <td align = "center">2</td>
      <td>Le Van Duy</td>
      <td>
        <a href = "mailto:20521233@gm.uit.edu.vn">20521233@gm.uit.edu.vn</a>
      </td>
      <td>
        <a href = "https://github.com/leduy-it">leduy-it</a>
      </td>
      <td>
        <a href = "https://www.linkedin.com/in/leduy-it/">Le Van Duy</a>
      </td>
      <td>
        <a href = "https://www.facebook.com/DuyEkko" rel = "nofollow">Lê Văn Duy</a>
      </td>
    </tr>
  </tbody>
</table>

# Introduction:
- the importance of handwritten address recognition in natural language processing and character recognition. Automating the recognition and extraction of information from images containing handwritten addresses can be valuable in various real-life applications, such as data entry automation, customer information management, and enhancing user experience in mobile applications.
- For countries like Vietnam, where handwritten addresses come in diverse forms and features, building an effective handwritten address recognition model is a significant challenge. The Transformer OCR method is also employed to enhance the recognition and information extraction from handwritten addresses. Transformer OCR is a model based on the Transformer architecture, successfully applied in natural language processing. It uses attention mechanisms to focus on important parts of character sequences and translates recognized characters into meaningful text.
- The research proposes a model for recognizing Vietnamese handwritten addresses using the Transformer. The model is trained on a large dataset containing images of Vietnamese handwritten addresses to ensure diversity and high accuracy. The performance of the model is evaluated on a test dataset and compared with previous methods to assess its accuracy and effectiveness.
# Description Problem:
![description problem](https://camo.githubusercontent.com/a36e6118ddc69a0b965c506246cf08c1b2db66a64aa8d3c4f6c94377f80df377/68747470733a2f2f692e696d6775722e636f6d2f76776c737835322e706e67)
Given an image of a Vietnamese handwritten line, we need to use an OCR model to transcribe the image into text like above.
# Dataset:
The dataset, which have 1838 traning images and 538 testing images. Theirs labels in json file, is provided by Cinnamon AI.

Here are 10 samples of the dataset:
![sample](https://camo.githubusercontent.com/42caf01b97c950f82d8a2880c192433426e7aecb48ffecaca1b9dbfa7dac04d3/68747470733a2f2f692e696d6775722e636f6d2f66545865746b302e6a7067)
Here is the structure of the json file containing the labels:
![label](https://camo.githubusercontent.com/66f97a1a493e3c63c5a37158f77e5d35aaa1c3ce435c4ed0bebeda89951a21e0/68747470733a2f2f692e696d6775722e636f6d2f554b7a414e53492e706e67)
Dataset which we merged based on the Cinnamon's dataset: https://drive.google.com/drive/folders/1_Zg_X1tSxtZh2UJ2Rlq-ojGQA_jp8bYg?usp=drive_link

More detail about dataset: https://drive.google.com/drive/folders/1Qa2YA6w6V5MaNV-qxqhsHHoYFRK5JB39

# Model:

In this section, we will explain how to combine the CNN model with the Language Model (Seq2Seq and Transformer) to create a model that helps you solve the OCR problem. For a detailed understanding of each step of the model's operation, it is recommended to refer to the introductions of seq2seq architectures in the NLP community, as this model is widely used and well-known.

Furthermore, I will also compare the limitations of the classical OCR model that uses CTCLoss with the two models mentioned above. This will assist you in choosing the appropriate model for real-world problems.

## CNN in OCR:

The CNN model used in the OCR problem takes an image as input, typically with a much larger length than width. Therefore, adjusting the stride size parameter of the pooling layers is extremely important. As for the OCR model, I usually choose a stride size of wxh=2x1 for the last pooling layers. Not changing the stride size to fit the image dimensions can result in poor recognition results for the model.

For the VGG model, changing the pooling size is relatively easy due to its simple architecture. However, for more complex models like ResNet, adjusting the pooling size is a bit more complicated because an image is downsampled not only by the pooling layers but also by other convolutional layers.

In PyTorch, for the VGG model, you can simply replace the stride size of the pooling layers to make the necessary adjustments.
<blockquote style="text-align: center;">
  cnn.features[i] = torch.nn.AvgPool2d(kernel_size=ks[pool_idx], stride=ss[pool_idx], padding=0)
</blockquote>

## Attention OCR

![AttentionOCR](https://pbcquoc.github.io/images/vietocr/cnn_seq2seq.jpg)

AttentionOCR is a combination of the CNN model and the Attention Seq2Seq model. The operation of this model is similar to the architecture of the seq2seq model in machine translation tasks. In machine translation from Vietnamese to English, we need to encode a Vietnamese sentence into a feature vector. In the case of AttentionOCR, the input data is an image.

Passing an image through the CNN model will produce a feature map with dimensions channel x height x width. This feature map becomes the input for the LSTM model. However, the LSTM model only accepts input with dimensions hidden x time_step. To address this, a simple and reasonable approach is to flatten the last two dimensions (height x width) of the feature map directly. This will result in a feature map with dimensions suitable for the requirements of the LSTM model.

![FeatureMaps](https://pbcquoc.github.io/images/vietocr/cnn_fts.jpg)

## Transformer OCR

You can leverage the Transformer architecture instead of the LSTM model to predict the next word in an image. The author has explained the detailed architecture and operation of the Transformer model extensively <a href="https://pbcquoc.github.io/transformer/">here</a>, so you can refer to that for a comprehensive understanding.

## Training model

Training the AttentionOCR or TransformerOCR model is very similar to training the seq2seq model. They all use cross-entropy loss for optimization, instead of using CTCLoss like the CRNN model. This means that at each time step, the model predicts a word and then compares it with the ground truth label to calculate the loss and update the model's weights accordingly.

## Limitations of Models Using CTCLoss

For the CRNN model that uses CTCloss as the objective function, the maximum number of characters that can be predicted is limited by the width x height of the feature maps. Therefore, careful adjustment of the model architecture is necessary to predict the appropriate number of characters for each dataset. In contrast, for the AttentionOCR or TransformerOCR models, you do not encounter this issue, making it easy to use pretrained models for different types of data.

Furthermore, both AttentionOCR and TransformerOCR have the seq2seq model architecture, which allows you to apply techniques from this translation model to our model as well.

# VietOCR

To respect the intellectual property rights, I will quote the original statement of the author:

"The VietOCR library was built with the purpose of supporting you in solving OCR-related problems in the industry. The library provides both the AttentionOCR and TransformerOCR architectures. Although the TransformerOCR architecture performs well in NLP, in my observation, the accuracy does not show significant improvement compared to AttentionOCR, while the prediction time is much slower. I have provided a pretrained model trained on a dataset of 10 million images for you to use quickly in new tasks. However, I encourage you to train the model on your own new dataset if you intend to use it in the industry."

In this project, we implemented a Transformer OCR model for recognizing handwritten Vietnamese text. Using the author's pretrained model to train the model with the Cinnamon AI marathon dataset because this dataset is not large enough. Training with the pretrained model will lead to faster convergence of the loss score. The model architecture is a great combination of CNN and Transformer (the foundational model of the famous BERT). The TransformerOCR model has many advantages over the CRNN model architecture that we previously implemented <a href="https://github.com/HungPham2002/Vietnamese-Handwriting-Recognition-OCR-using-CRNN-with-CTC-Loss">here</a>.

The VietOCR model exhibits an excellent level of generalization and even achieves relatively high accuracy on a new dataset despite never being trained on it before.

How to use and more detail about the library, you can read <a href="https://github.com/pbcquoc/vietocr">here</a>.

In the next section, We will discuss how to create a suitable dataset for the library, use the library to train on a new dataset, modify the augmentation techniques, make predictions for new images, and provide some tips when using the library.

## Prepare a dataset:
To train the model, you need to prepare a dataset with a minimum of about 3k samples. In real-world projects, it is advisable to use 20k samples or more. The directory structure for storing the data should be organized as follows:
<blockquote style="text-align: center;">
.

├── img

│    ├── 00000.jpg

│    ├── 00001.jpg

├── train_annotation.txt # nhãn tập train 

└── val_annotation.txt # nhãn tập test
</blockquote>

Data file labels should follow the following format:

<blockquote style="text-align: center;">
  
path_to_file_name[tab]nhãn

</blockquote>

<blockquote style="text-align: center;">
  
img/74086.jpg   429/BCT-ĐTĐL

img/04225.jpg   Như trên;

img/97822.jpg   V/v: Duyệt dự toán chi phí Ban QLDA nhiệt điện 1 năm 2012 và
</blockquote>

## Custom Augmentor
By default, the model uses augmentation. However, you may need to augment the data differently to ensure that the image distortion is not too significant compared to the original data. Therefore, the library allows you to define your own augmentation as shown in the example below, and pass it during training.

<blockquote style="text-align: center;">

  from vietocr.loader.aug import ImgAugTransform

  from imgaug import augmenters as iaa

  class MyAugmentor(ImgAugTransform):

    def __init__(self):
    
        self.aug = iaa.GaussianBlur(sigma=(0, 1.0))
        
</blockquote>

## Training

More information regarding the implementation can be found in the jupyter notebook in the github.

# Evaluation Metrics:
Evaluation is based on character error rate (CER)

- CER is calculated based on Edit distance (or Levenshtein distance)
Given a predicted string A, and the ground truth string B, CER is specified by:

![CER](https://drive.google.com/uc?export=view&id=1O1bhhZQplshvNRV2BkeWPd_XTU1xNrwn)

- Word Error Rate:

![WER](https://drive.google.com/uc?export=view&id=1-w5-zS_OXG3R5MnX_1pZeSUB7J4PNBp_)

- Sequece Error Rate:

![SER](https://drive.google.com/uc?export=view&id=1UQfNG2FqT-RxaqPXlcaCDPhuoWh22u2j)

# Results:
Here are the important three evaluation metris for a test set (the host's private test):

  + CER (Character Error Rate): 0.1021489139159989

  + WER (Word Error Rate): 0.0660670516491975

  + SER (Sequence Error Rate): 0.9435336976320583

We got a pretty good results with CER at 8% and WER at 27%!

There are plenty of examples where the model predicts every single character perfectly like this!

![test](https://drive.google.com/uc?export=view&id=1I0aKAAbBgE8MokfvFfDZ8cpPrgioZ902)

# References:
[1] https://github.com/pbcquoc/vietocr

[2] https://pbcquoc.github.io/vietocr/

[3] https://pbcquoc.github.io/transformer/

[4] https://viblo.asia/p/nhan-dang-tieng-viet-cung-voi-transformer-ocr-Qpmlejjm5rd

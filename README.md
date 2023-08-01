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

# Updating

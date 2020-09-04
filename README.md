# mask-processing

# Description


# Demo

1. Preparing images

<div align="center">
<img src="https://github.com/hiroyasuakada/mask-processing/blob/master/demo/input_image/test.jpg" alt="属性" title="タイトル">
</div>

<br>

2. Processing images with mask

<div align="center">
  <img src="https://github.com/hiroyasuakada/mask-processing/blob/master/demo/output_image/image_with_full_prediction/test.jpg" alt="属性" title="タイトル">
<img src="https://github.com/hiroyasuakada/mask-processing/blob/master/demo/output_image/image_with_mask_cropped/test.jpg" alt="属性" title="タイトル">
  <br>
<img src="https://github.com/hiroyasuakada/mask-processing/blob/master/demo/output_image/binary_mask/test.jpg" alt="属性" title="タイトル">
<img src="https://github.com/hiroyasuakada/mask-processing/blob/master/demo/output_image/cropped_figure/test.jpg" alt="属性" title="タイトル">
</div>

<br>

# Usage

## 1. Install [Detectron2](<https://github.com/facebookresearch/detectron2/>)

please see INSTALL.md. in the Installation section.
Using its dockerfile is highly recommended.

## 2. Clone this repository

git clone https://github.com/hiroyasuakada/mask-processing.git

## 3. Processing learning phase on cnn, transfer learning

animal_cnn.py: learning train data based on gen_data.py

animal_cnn_augmented.py: learning train data based on gen_data_augmented.py

## 4. Showing the result of learning on commandprompt

predict.py

# References
["Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks"](https://arxiv.org/abs/1703.10593)

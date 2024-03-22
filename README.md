####Install from the installation file

dino_Detr_insta.ipynb


### Upload image file in coco format
/COCODIR/
  ├── train2017/
  ├── val2017/
  └── annotations/
  	├── instances_train2017.json
  	└── instances_val2017.json

   

###modify  File "/workspace/DINO/util/slconfig.py", line 317, in pretty_text
    text, _ = FormatCode(text, style_config=yapf_style, verify=True)
TypeError: FormatCode() got an unexpected keyword argument 'verify'
Remove 'verify=True'

###Modify file from 'np.float' to 'float' according to the error location
train model 


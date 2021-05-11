# face2comics by Sxela (Alex Spirin)
## This is a paired face to comics dataset, which can be used to train pix2pix or similar networks.
This dataset contains a lot of crappy nightmare-fuelish samples, which tend to be useful for full image to comic convertion, as they teach models how to trace something if it's not a face.

## Update: v2.0.0 dataset added!

## v2.0.0 dataset
Darkish red style, 1024x1024, 10000 pairs (total 20k images)
[Download faces from github (~1Gb)](https://github.com/Sxela/face2comics/releases/download/v2.0.0/face2comics_v2.0.0_by_Sxela_faces.tar)
[Download comics from github (~1Gb)](https://github.com/Sxela/face2comics/releases/download/v2.0.0/face2comics_v2.0.0_by_Sxela_comics.tar)

### 2x2 dataset sample:
![2x2 v2.0.0 sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v2.0.0_by_Sxela_preview_2x2x512.jpg)


### 10x10 dataet sample:
![10x10 v2.0.0 sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v2.0.0_by_Sxela_preview_10x10x256.jpg)


### An inference sample of a fastai unet trained on this very dataset : 
You can train your own unet by using their awesome notebook [here](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson7-superres-gan.ipynb)

![v2.0.0 unet sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v2.0.0_by_Sxela_unet_sample_2x2.jpg)

## v1.0.0 dataset
Dark style, 512x512, 10000 pairs (total 20k images)
[Download from github (~700Mb)](https://github.com/Sxela/face2comics/releases/download/v1.0.0/face2comics_v1.0.0_by_Sxela.tar)


### 2x2 dataset sample:
![2x2 v1.0.0 sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v1.0.0_4sample.jpg)


### 10x10 dataet sample:
![10x10 v1.0.0 sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v1.0.0_comics_sample_large.jpg)


### An inference sample of a fastai unet trained on this very dataset : 
You can train your own unet by using their awesome notebook [here](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson7-superres-gan.ipynb)

![v1.0.0 unet sample](https://github.com/Sxela/face2comics/blob/main/samples/face2comics_v1.0.0_unet_sample.jpg)

# Recognition
justinpinkney for his layer blending idea, repo and tutorials 
https://github.com/justinpinkney/stylegan2

NVlabs for their Stylegan2, of course, though I didn't use their original code 
https://github.com/NVlabs/stylegan2

fastai for their awesome framework and simple GAN training pipeline
https://fast.ai

# Image Retrieval with Text and Sketch
This code is for our 2022 ECCV paper [A Sketch Is Worth a Thousand Words: Image Retrieval with Text and Sketch](https://patsorn.me/projects/tsbir/)

<img src="https://patsorn.me/projects/tsbir/img/teaser_web_mini.jpg" width="800px"/>

This repo is based on open_clip implementation from https://github.com/mlfoundations/open_clip

---------------------
folder structure
---------------------
    |---model/       : Contain the trained model*
    |---sketches/    : Contain example query sketch
    |---images/      : Contain 100 randomly sampled images from COCO TBIR benchmark
    |---notebooks/   : Contain the demo ipynb notebook 
    |---code/        
        |---training/model_configs/      : Contain model config file for the network
        |---clip/                        : Contain source code for running the notebook    
    
*need to be downloaded first

## Prerequisites
- Pytorch
- ftfy

## Getting Started

- Simply open jupyter notebook in `notebooks/Retrieval_Demo.ipynb` for an example of how to retrieve images using our model, 

- You can use your own set of images and sketches by modifying the `images/` and `sketches/` folder accordingly.

- Colab version of the notebook is available [[here]](https://colab.research.google.com/drive/1dpzDkpMVYfiV82XJlyM09wYCMlXyjAY-?usp=sharing)
 
## Download Models
- <a href='https://patsorn.me/projects/tsbir/data/tsbir_model_final.pt' > Pre-trained models </a>  

## Citation
If you find it this code useful for your research, please cite: 

"A Sketch Is Worth a Thousand Words: Image Retrieval with Text and Sketch"

[Patsorn Sangkloy](https://patsorn.me),   [Wittawat Jitkrittum](http://wittawat.com/), Diyi Yang, James Hays in ECCV, 2022.
```
@article{
 tsbir2022,
 author = {Patsorn Sangkloy and Wittawat Jitkrittum and Diyi Yang and James Hays},
 title = {A Sketch is Worth a Thousand Words: Image Retrieval with Text and Sketch},
 journal = {European Conference on Computer Vision, ECCV},
 year = {2022},
}
```


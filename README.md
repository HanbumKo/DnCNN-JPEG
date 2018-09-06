# Description
A Tenrowflow implementation of DnCNN, *'Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising' TIP2017*, paper.
Original code is [here](https://github.com/crisb-DUT/DnCNN-tensorflow) but this code covers only a Gaussian denoiser.
So I fixed it for JPEG deblocking(only for quality factor : 10).








## Model architecture
![Alt text](/git_img/model.png)





## Usage
### Train
```
$ python generate_data.py
$ python main.py
```


### Test
```
$ python main.py --phase test
```




## Result
input : ![Alt text](/git_img/result_noisy.png)
output : ![Alt text](/git_img/result_denoised.png)



## Reference
[https://github.com/crisb-DUT/DnCNN-tensorflow](https://github.com/crisb-DUT/DnCNN-tensorflow)


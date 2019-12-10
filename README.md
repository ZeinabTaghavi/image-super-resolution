# Image Super-Resolution (ISR)

to read about archtecture [github](https://github.com/idealo/image-super-resolution)

what I have added to code:
i used it for resolution enhansement
fist I denoised image. [how to denoise thresh base](https://github.com/ZeinabTaghavi/Denoising_Printed_Documents_Threshbase)
then used it as input of GAN.

this was result:
(image was high resolution, we drop other parts)
source image:

<img src="https://github.com/ZeinabTaghavi/image-super-resolution/blob/master/data/input/sample/image1_not_denoised.png?raw=true" height="40%" width="40%">

denoised image:

<img src="https://github.com/ZeinabTaghavi/image-super-resolution/blob/master/data/input/sample/image1.png?raw=true" width="40%" height="40%">

sliced a part for GAN:

<img src="https://github.com/ZeinabTaghavi/image-super-resolution/blob/master/data/input/sample/part_of_image.png?raw=true" width="30%" height="30%">

GAN resolution enhancement

<img src="https://github.com/ZeinabTaghavi/image-super-resolution/blob/master/data/input/results/result_img1.png?raw=true" width="30%" height="30%">

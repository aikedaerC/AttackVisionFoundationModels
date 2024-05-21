# Attack-Vison-Foundation-Models

## Getting Started

---

### Installation

The installation of this project is extremely easy. You only need to:

- Configurate the environment, vicuna weights, following the instruction in https://github.com/Vision-CAIR/MiniGPT-4    


### Runing

- Add noise to the original image.
```
python gptv_attack.py --add_noise
```
- Add text to the original image. 
```
python gptv_attack.py --add_text
```



### Evaluation

only implement on imp-v1-3b

here is the implementation: https://github.com/aikedaerC/imp-v1-3b-adv

> For the convinent of calculating SSIM, we also implement a GUI tool which can both process single image pair and batch image pairs.

```sh
python batchSSIM.py
```

![ssimcal](https://github.com/HongdaChen/picx-images-hosting/raw/master/20240521/ssimcal.1hs1hshqcr.webp)
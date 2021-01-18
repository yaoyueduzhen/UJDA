# UJDA
Unsupervised domain adaptation with unified joint
distribution alignment

## Prerequisites:

* Python3
* PyTorch ==0.4.1 (with suitable CUDA and CuDNN version)
* torchvision == 0.2.0
* Numpy
* tqdm

## Dataset:

You need to modify the path of the image in every ".txt" in "./data".

## Training:
run :

    python train.py --config ../config/dann.yml   --dataset Office-31   --src_address ../data/amazon.txt    --tgt_address     ../data/dslr.txt  --src_test_address ../data/amazon.txt

## Citation:
If you use this code for your research, please consider citing:

```
@article{du2020dual,
  title={Unsupervised domain adaptation with unified joint distribution alignment},
  author={Du, Yuntao and Tan, Zhiwen and Chen, Qian and Zhang, Xiaowen and Yao, Yirong and Wang, Chongjun},
  journal={arXiv preprint arXiv:2001.00153},
  year={2020}
}
```

## Contact
If you have any problem about our code, feel free to contact yaoyueduzhen@outlook.com.

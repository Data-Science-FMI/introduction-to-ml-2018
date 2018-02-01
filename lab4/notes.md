- [Cifar 10 Challenge](https://www.kaggle.com/c/cifar-10)
- Free GPU (Tesla K80) by [Google Colaboratory](https://colab.research.google.com/)

> ```!pip install http://download.pytorch.org/whl/cu80/torch-0.3.0.post4-cp36-cp36m-linux_x86_64.whl```

```python
import torch

print(torch.cuda.device_count())
print(torch.cuda.get_device_name(0))
```

[More info at Reddit](https://www.reddit.com/r/MachineLearning/comments/7rnmw0/d_google_colab_gives_you_a_free_k80_gpu_for_up_to/)

# Research

- [Turning Design Mockups Into Code](https://blog.floydhub.com/Turning-design-mockups-into-code-with-deep-learning/)
- [Detectron](https://research.fb.com/facebook-open-sources-detectron/) - state-of-the-art platform for object detection research by Facebook Research

# Learn

- [Computational Graphs in PyTorch](https://jdhao.github.io/2017/11/12/pytorch-computation-graph/)
- [Understanding Learning Rates and How It Improves Performance in Deep Learning](https://towardsdatascience.com/understanding-learning-rates-and-how-it-improves-performance-in-deep-learning-d0d4059c1c10)
- [Simple PyTorch examples by Justin Johnson](https://github.com/jcjohnson/pytorch-examples)

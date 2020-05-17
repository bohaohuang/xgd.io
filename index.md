# Do Deep Learning Models Generalize to Overhead Imagery from Novel Geographic Locations? The XGD Benchmark Problem
![domain](https://user-images.githubusercontent.com/31373708/82159269-07e33c80-985b-11ea-92f4-b8c2f27555f0.png)

## Dataset
We use two publicly available benchmark datasets in building segmentation of the overhead imagery: [Inria](https://project.inria.fr/aerialimagelabeling/) and [DeepGlibe](https://competitions.codalab.org/competitions/18544) in the XGD benchmark problem. However, thoretically, you can use any two datasets to form a XGD testing scenario as long as the two datasets share the same annotated classes and resolution.

## Setup
![data2](https://user-images.githubusercontent.com/31373708/82159253-eeda8b80-985a-11ea-8482-f841f0b73168.png)
The experimental design of the xGD problem is illustrated in (a) and (b). They illustrate how we evaluate cross-domain and in-domain performance, respectively. Both in-domain and cross-domain models are evaluated on exactly the same 14% subset of testing imagery, helping to ensure a fair comparison of the in- and cross-domain scenarios. This design also ensures that the models in both scenarios have access to similar quantities of image area and building labels.

## Code
Check our framework for segmentation in remote sensing: [GitHub](https://github.com/bohaohuang/mrs)

## Paper
Check more details in our paper: _URL TBD_

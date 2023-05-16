# Data Augmentation

## Title List

1. [TeachAugment: Data Augmentation Optimization Using Teacher Knowledge (CVPR2022)](#teachaugment-data-augmentation-optimization-using-teacher-knowledge-cvpr2022)
2. [SuperMix: Supervising the Mixing Data Augmentation (CVPR2021)](#supermix-supervising-the-mixing-data-augmentation-cvpr2021)
3. [AutoAugment: Learning Augmentation Strategies From Data (CVPR2019)](#autoaugment-learning-augmentation-strategies-from-data-cvpr2019)
4. [CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features (ICCV2019)](#cutmix-regularization-strategy-to-train-strong-classifiers-with-localizable-features-iccv2019)
5. [mixup: Beyond Empirical Risk Minimization (ICLR2018)](#mixup-beyond-empirical-risk-minimization-iclr2018)

---

### Title (Conference or Journal)

[[Paper]]()
[[Code]]()
[[bibtex]]()

- summary  
    ***
    調査中
    ***
- Keywords : `keyword`

### TeachAugment: Data Augmentation Optimization Using Teacher Knowledge (CVPR2022)

[[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Suzuki_TeachAugment_Data_Augmentation_Optimization_Using_Teacher_Knowledge_CVPR_2022_paper.pdf)
[[Code]](https://github.com/DensoITLab/TeachAugment)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2022/html/Suzuki_TeachAugment_Data_Augmentation_Optimization_Using_Teacher_Knowledge_CVPR_2022_paper.html)

- summary  
    ***
    調査中
    ***
- Keywords : `Adversarial Training`

### SuperMix: Supervising the Mixing Data Augmentation (CVPR2021)

[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Dabouei_SuperMix_Supervising_the_Mixing_Data_Augmentation_CVPR_2021_paper.pdf)
[[Code]](https://github.com/alldbi/SuperMix)
[[bibtex]](https://github.com/alldbi/SuperMix)

- summary  
    ***
    [CutMix](#cutmix-regularization-strategy-to-train-strong-classifiers-with-localizable-features-iccv2019)の改良。
    1つの画像に対してピクセルレベルの重みマスクを生成し、識別に影響の大きいピクセルをペア画像に強く結合することで、より効果的な混合データ増強を行う手法。
    ***
- Keywords : `Mixing Augmentation`

### AutoAugment: Learning Augmentation Strategies From Data (CVPR2019)

[[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cubuk_AutoAugment_Learning_Augmentation_Strategies_From_Data_CVPR_2019_paper.pdf)
[[Code]](https://github.com/DeepVoltaire/AutoAugment)
[[bibtex]](https://openaccess.thecvf.com/content_CVPR_2019/html/Cubuk_AutoAugment_Learning_Augmentation_Strategies_From_Data_CVPR_2019_paper.html)

- summary  
    ***
    事前に定義された画像変換が与えられた場合に、最適な拡張方針の探索を自動化した手法。
    ***
- Keywords : `keyword`

### CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features (ICCV2019)

[[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yun_CutMix_Regularization_Strategy_to_Train_Strong_Classifiers_With_Localizable_Features_ICCV_2019_paper.pdf)
[[Code]](https://github.com/clovaai/CutMix-PyTorch)
[[bibtex]](https://openaccess.thecvf.com/content_ICCV_2019/html/Yun_CutMix_Regularization_Strategy_to_Train_Strong_Classifiers_With_Localizable_Features_ICCV_2019_paper.html)

- summary  
    ***
    [mixup](#mixup-beyond-empirical-risk-minimization-iclr2018)とCutoutの組み合わせ。
    2つの画像とラベルのペアに対して一方の画像の識別に影響を大きい領域を矩形マスクで切り出し、もう一方の画像に貼り付ける混合データ増強手法。また、ラベルも同様に凸線形補間によるデータ増強を行う。
    ***
- Keywords : `Mixing Augmentation`

### mixup: Beyond Empirical Risk Minimization (ICLR2018)

[[Paper]](https://openreview.net/pdf?id=r1Ddp1-Rb)
[[Code]](https://github.com/facebookresearch/mixup-cifar10)
[[bibtex]](https://openreview.net/forum?id=r1Ddp1-Rb&;noteId=r1Ddp1-Rb)

- summary  
    ***
    ベータ分布から得られた確率を重みとして、ランダムに選ばれたデータとラベルのペアに対して凸線形補間によるデータ増強を行い画像を結合する。
    ***
- Keywords : `Mixing Augmentation`

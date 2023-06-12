# Data Augmentation

## Title List

1. [TeachAugment: Data Augmentation Optimization Using Teacher Knowledge (CVPR2022)](#teachaugment-data-augmentation-optimization-using-teacher-knowledge-cvpr2022)
2. [SuperMix: Supervising the Mixing Data Augmentation (CVPR2021)](#supermix-supervising-the-mixing-data-augmentation-cvpr2021)
3. [Randaugment: Practical Automated Data Augmentation With a Reduced Search Space (CVPR2020)](#randaugment-practical-automated-data-augmentation-with-a-reduced-search-space-cvpr2020)
4. [AutoAugment: Learning Augmentation Strategies From Data (CVPR2019)](#autoaugment-learning-augmentation-strategies-from-data-cvpr2019)
5. [CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features (ICCV2019)](#cutmix-regularization-strategy-to-train-strong-classifiers-with-localizable-features-iccv2019)
6. [mixup: Beyond Empirical Risk Minimization (ICLR2018)](#mixup-beyond-empirical-risk-minimization-iclr2018)

---

### Over-Training with Mixup May Hurt Generalization (ICLR2023)

[[Paper]](https://openreview.net/pdf?id=JmkjrlVE-DG)
[[bibtex]](https://openreview.net/forum?id=JmkjrlVE-DG#)

- <details><summary>summary</summary>
  
    ***
    調査中
    ***
  </details>
- Keywords : `MixUp` `Generalization` `Regularization`

### TeachAugment: Data Augmentation Optimization Using Teacher Knowledge (CVPR2022)

[[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Suzuki_TeachAugment_Data_Augmentation_Optimization_Using_Teacher_Knowledge_CVPR_2022_paper.pdf)
[[Code]](https://github.com/DensoITLab/TeachAugment)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2022/html/Suzuki_TeachAugment_Data_Augmentation_Optimization_Using_Teacher_Knowledge_CVPR_2022_paper.html)

- <details><summary>summary</summary>  
  
    ***
    TeacherネットワークとStudentネットワークを用意し、Teacherネットワークには識別可能であるが、Studentネットワークに対しては誤識別させるようなデータ拡張を探索し、訓練する教師ありデータ拡張手法。
    ***
  </details>
- Keywords : `Adversarial Training` `Data Augmentation`

### SuperMix: Supervising the Mixing Data Augmentation (CVPR2021)

[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Dabouei_SuperMix_Supervising_the_Mixing_Data_Augmentation_CVPR_2021_paper.pdf)
[[Code]](https://github.com/alldbi/SuperMix)
[[bibtex]](https://github.com/alldbi/SuperMix)

- <details><summary>summary</summary>  
  
    ***
    [CutMix](#cutmix-regularization-strategy-to-train-strong-classifiers-with-localizable-features-iccv2019)の改良。
    1つの画像に対してピクセルレベルの重みマスクを生成し、識別に影響の大きいピクセルをペア画像に強く結合することで、より効果的な混合データ増強を行う手法。
    ***
  </details>
- Keywords : `Mixing Augmentation`

### Randaugment: Practical Automated Data Augmentation With a Reduced Search Space (CVPR2020)

[[Paper]](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w40/Cubuk_Randaugment_Practical_Automated_Data_Augmentation_With_a_Reduced_Search_Space_CVPRW_2020_paper.pdf)
[[Code]](https://github.com/ildoonet/pytorch-randaugment)
[[bibtex]](https://openaccess.thecvf.com/content_CVPRW_2020/html/w40/Cubuk_Randaugment_Practical_Automated_Data_Augmentation_With_a_Reduced_Search_Space_CVPRW_2020_paper.html)

- <details><summary>summary</summary>  
  
    ***
    [AutoAugment](#autoaugment-learning-augmentation-strategies-from-data-cvpr2019)の改良。
    ランダムな変換を組み合わせることで、探索空間を単純化し、探索にかかる計算量を大幅に削減した手法.
    ***
  </details>
- Keywords : `Data Augmentation`

### AutoAugment: Learning Augmentation Strategies From Data (CVPR2019)

[[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cubuk_AutoAugment_Learning_Augmentation_Strategies_From_Data_CVPR_2019_paper.pdf)
[[Code]](https://github.com/DeepVoltaire/AutoAugment)
[[bibtex]](https://openaccess.thecvf.com/content_CVPR_2019/html/Cubuk_AutoAugment_Learning_Augmentation_Strategies_From_Data_CVPR_2019_paper.html)

- <details><summary>summary</summary>  
  
    ***
    事前に定義された画像変換が与えられた場合に、最適な拡張方針の探索を自動化した手法。
    ***
  </details>
- Keywords : `Data Augmentation`

### CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features (ICCV2019)

[[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yun_CutMix_Regularization_Strategy_to_Train_Strong_Classifiers_With_Localizable_Features_ICCV_2019_paper.pdf)
[[Code]](https://github.com/clovaai/CutMix-PyTorch)
[[bibtex]](https://openaccess.thecvf.com/content_ICCV_2019/html/Yun_CutMix_Regularization_Strategy_to_Train_Strong_Classifiers_With_Localizable_Features_ICCV_2019_paper.html)

- <details><summary>summary</summary>  
  
    ***
    [mixup](#mixup-beyond-empirical-risk-minimization-iclr2018)とCutoutの組み合わせ。
    2つの画像とラベルのペアに対して一方の画像の切り取られた領域を、もう一方の画像に重ね合わせる混合データ増強手法。
    また、ラベルも同様に凸線形補間によるデータ増強を行う。
    ***
  </details>
- Keywords : `Mixing Augmentation`

### mixup: Beyond Empirical Risk Minimization (ICLR2018)

[[Paper]](https://openreview.net/pdf?id=r1Ddp1-Rb)
[[Code]](https://github.com/facebookresearch/mixup-cifar10)
[[bibtex]](https://openreview.net/forum?id=r1Ddp1-Rb&;noteId=r1Ddp1-Rb)

- <details><summary>summary</summary>  
  
    ***
    ベータ分布から得られた確率を重みとして、ランダムに選ばれたデータとラベルのペアに対して凸線形補間によるデータ増強を行い画像を結合する。
    ***
  </details>
- Keywords : `Mixing Augmentation`

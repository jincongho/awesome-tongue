# Awesome Tongue

Automated Tongue Diagnosis (ATD) is a growing research field in recent years. This is a curated list of resources for Automatic Tongue Diagnosis from 2009, inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision). Hopefully it helps to attract more researchers and pushes for more standardized and consistent works.

Maintainer - [Jin Cong Ho](https://github.com/jincongho)

## Sharing
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?u=https://github.com/jincongho/awesome-tongue)
+ [Share on Twitter](http://twitter.com/home?status=https://github.com/jincongho/awesome-tongue%0AResource%20for%20Automatic%20Tongue%20Diagnosis)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/jincongho/awesome-tongue&title=Awesome%20Tongue&summary=&source=)

## Topics

### General Survey
* Marzia Hoque Tania, Khin Lwin, Mohammed Alamgir Hossain, "Advances in automated tongue diagnosis techniques", Integrative Medicine Research, 2018 [[Paper](https://www.sciencedirect.com/science/article/pii/S2213422017302603)]
* Chang Jin Jung, Young Ju Jeon, Jong Yeol Kim, Keun Ho Kim, "Review on the current trends in tongue diagnosis systems", 2012 [[Paper](https://www.sciencedirect.com/science/article/pii/S2213422012000029)]

### Tongue Diagnosis Systems and Image Acquisition


### Image Segmentation and Features Extraction

Segmenting tongue from background is crutial for further analysis on relevant features. Most papers use multiple methods for segmentation, especially relying on heuristics for contour initialization. However, they are only listed once here.

#### Color Thresholding

* L. Chen, D. Wang, Y. Liu, X. Gao, H. Shang, "A novel automatic tongue image segmentation algorithm: color enhancement method based on L*a*b* color space", 2015 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) [[Paper](https://ieeexplore.ieee.org/document/7359818/)]
* M. Zhu, J. Du, C. Ding, "A comparative study of contemporary color tongue image extraction methods based on HSI", Int J Biomed Imaging, 2014 [[Paper](https://www.hindawi.com/journals/ijbi/2014/534507/)]
* M.F. Zhu, J.Q. Du, K. Zhang, C.H. Ding, "A novel approach for tongue image extraction based on combination of color and space information", 2009 3rd International Conference on Bioinformatics and Biomedical Engineering, [[Paper](https://ieeexplore.ieee.org/document/5162213/)]
* D. Jian-Qiang, L. Yan-Sheng, Z. Ming-Feng, Z. Kang, D. Cheng-Hua, "A novel algorithm of color tongue image segmentation based on HSI", BMEI 2008 [[Paper](https://ieeexplore.ieee.org/document/4548766/)]

#### Edge Detection 

* Cui Z., Zuo W., Zhang H., Zhang D., "Automated Tongue Segmentation Based on 2D Gabor Filters and Fast Marching", 2013 [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-42057-3_42)] (Edge + ACM)
* C. Liang, D. Shi, "A prior knowledge-based algorithm for tongue body segmentation", ICCSEE 2012 [[Paper](https://ieeexplore.ieee.org/document/6188112/)] (Edge + ACM)
* Y. Hsu, Y. Chen, L. Lo, J.Y. Chiang, A.C. Calibration, "Automatic tongue feature extraction", ICS2010 [[Paper](https://ieeexplore.ieee.org/document/5685377/)] (Edge + ACM)

#### Clustering

* W. Xu, R. Kanawong, D. Xu, S. Li, T. Ma, G. Zhang, et al. "An automatic tongue detection and segmentation framework for computer-aided tongue image analysis", 2011 [[Paper](https://ieeexplore.ieee.org/document/6026741/)] (Clustering + ACM)

#### Region Growing

* Kebin Wu, David Zhang, "Robust tongue segmentation by fusing region-based and edge-based approaches", 2015 [[Paper](https://www.sciencedirect.com/science/article/pii/S0957417415004340)] (Edge + RG + ACM)
* J. Ning, D. Zhang, C. Wu, F. Yue, "Automatic tongue image segmentation based on gradient vector flow and region merging" Neural Comput Appl, 21 (2012) [[Paper](https://link.springer.com/article/10.1007%2Fs00521-010-0484-3)] (RG + ACM)

#### Model-based Approach

* X. Zhong, H. Fu, J. Yang, W. Wang, "Automatic segmentation in tongue image by mouth location and active appearance model", 2009 [[Paper](https://ieeexplore.ieee.org/document/5380423/)] (Active Appearance Model)

#### Active Contour Model (Snakes)

* Saparudin, Erwin and Muhammad Fachrurrozi, "Tongue Segmentation Using Active Contour Model", 2017 [[Paper](http://iopscience.iop.org/article/10.1088/1757-899X/190/1/012041)]
* Jingwei Guo, Yikang Yang, Qingwei Wu, Jionglong Su, Fei Ma, "Adaptive active contour model based automatic tongue image segmentation", 2016 [[Paper](https://ieeexplore.ieee.org/document/7852933/)]
* M. Shi, G.Z. Li, F. Li, C. Xu, "Computerized tongue image segmentation via the double geo-vector flow", 2014, [[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3922256/)]
* M.J. Shi, G.Z. Li, F.F. Li, "C2G2FSnake: automatic tongue image segmentation utilizing prior knowledge", Sci China Inf Sci, 56 (2013) [[Paper](https://doi.org/10.1007/s11432-011-4428-z)]
* W. Li, S. Hu, S. Wang, S. Xu, "Towards the objectification of tongue diagnosis: Automatic segmentation of tongue image", 2009 [[Paper](https://ieeexplore.ieee.org/document/5415334/)]
* X.M. Zhai, H.D. Lu, L.Z. Zhang, "Application of image segmentation technique in tongue diagnosis", 2009 [[Paper](https://ieeexplore.ieee.org/document/5231477/)]

#### Deep Learning

* Li J., Xu B., Ban X., Tai P., Ma B., "A Tongue Image Segmentation Method Based on Enhanced HSV Convolutional Neural Network", 2017 [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-66805-5_32)]
* X. Li, T. Yang, Y. Hu, M. Xu, W. Zhang and F. Li, "Automatic tongue image matting for remote medical diagnosis," 2017 [[Paper](https://ieeexplore.ieee.org/document/8217710/)]

### Disease Classification


### Mobile-enabled Tongue Diagnosic Systems

* D. Xu, "iTongue", 2015 [[Website](http://itongueapp.com)]
* M.H. Tania, K.T. Lwin, M.A. Hossain, "Computational complexity of image processing algorithms for an intelligent mobile enabled tongue diagnosis scheme", 2016 [[Paper](https://ieeexplore.ieee.org/document/7916193/)] 
* M.-C. Hu, M.-H. Cheng, K.-C. Lan, "Color correction parameter estimation on the smartphone and its application to automatic tongue diagnosis", 2016 [[Paper](https://link.springer.com/article/10.1007%2Fs10916-015-0387-z)]
* M.-C. Hu, G.-Y. Zheng, Y.-T. Chen, K.-C. Lan, "Automatic tongue diagnosis using a smart phone", 2014 [[Paper](http://www.csie.ncku.edu.tw/~klan/data/paper/pdf/tongue.pdf)]
* R. Ini, "TongueDx: a tongue diagnosis system for personal health care on smartphones", 2014 [[Paper](https://dl.acm.org/citation.cfm?doid=2582051.2582076)]
* Q. Zhang, H.L. Shang, J.J. Zhu, M.M. Jin, W.X. Wang, Q.S. Kong, "A new tongue diagnosis application on android platform", 2013 [[Paper](https://ieeexplore.ieee.org/document/6732705/)]

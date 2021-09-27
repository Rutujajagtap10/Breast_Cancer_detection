# Breast_Cancer_detection


# What is breast cancer? 
Cancer occurs when changes called mutations take place in genes that regulate cell growth. The mutations let the cells divide and multiply in an uncontrolled, chaotic way. The cells keep on proliferating, producing copies that get progressively more abnormal. In most cases, the cell copies eventually end up forming a tumor.

Breast cancer occurs when a malignant (cancerous) tumor originates in the breast. As breast cancer tumors mature, they may metastasize (spread) to other parts of the body. The primary route of metastasis is the lymphatic system which, ironically enough, is also the body's primary system for producing and transporting white blood cells and other cancer-fighting immune system cells throughout the body. Metastasized cancer cells that aren't destroyed by the lymphatic system's white blood cells move through the lymphatic vessels and settle in remote body locations, forming new tumors and perpetuating the disease process.

Breast cancer is not just a woman's disease. It is quite possible for men to get breast cancer, although it occurs less frequently in men than in women. Our discussion will focus primarily on breast cancer as it relates to women but it should be noted that much of the information is also applicable for men.

# Role of Artificial Intelligence in Breast-Cancer detection :- 

A mammogram is an x-ray picture of the breast. It can be used to check for breast cancer in women who have no signs or symptoms of the disease. It can also be used if you have a lump or other sign of breast cancer.

Screening mammography is the type of mammogram that checks you when you have no symptoms. It can help reduce the number of deaths from breast cancer among women ages 40 to 70. But it can also have drawbacks. Mammograms can sometimes find something that looks abnormal but isn't cancer. This leads to further testing and can cause you anxiety. Sometimes mammograms can miss cancer when it is there. It also exposes you to radiation. You should talk to your doctor about the benefits and drawbacks of mammograms. Together, you can decide when to start and how often to have a mammogram.

Now while its difficult to figure out for physicians by seeing only images of x-ray that weather the tumor is toxic or not training a artificial intelligence algorithms according to the identification of tumour can be of great help.

# Project Description :-

a) Creators:

Dr. William H. Wolberg, General Surgery Dept., University of
Wisconsin,  Clinical Sciences Center, Madison, WI 53792
wolberg@eagle.surgery.wisc.edu

W. Nick Street, Computer Sciences Dept., University of
Wisconsin, 1210 West Dayton St., Madison, WI 53706
street@cs.wisc.edu  608-262-6619

Olvi L. Mangasarian, Computer Sciences Dept., University of
Wisconsin, 1210 West Dayton St., Madison, WI 53706
olvi@cs.wisc.edu 
b) Donor: Nick Street

c) Date: November 1995

Past Usage:
first usage:

W.N. Street, W.H. Wolberg and O.L. Mangasarian 
Nuclear feature extraction for breast tumor diagnosis.
IS&T/SPIE 1993 International Symposium on Electronic Imaging: Science
and Technology, volume 1905, pages 861-870, San Jose, CA, 1993.
OR literature:

O.L. Mangasarian, W.N. Street and W.H. Wolberg. 
Breast cancer diagnosis and prognosis via linear programming. 
Operations Research, 43(4), pages 570-577, July-August 1995.
Medical literature:

W.H. Wolberg, W.N. Street, and O.L. Mangasarian. 
Machine learning techniques to diagnose breast cancer from
fine-needle aspirates.  
Cancer Letters 77 (1994) 163-171.

W.H. Wolberg, W.N. Street, and O.L. Mangasarian. 
Image analysis and machine learning applied to breast cancer
diagnosis and prognosis.  
Analytical and Quantitative Cytology and Histology, Vol. 17
No. 2, pages 77-87, April 1995. 

W.H. Wolberg, W.N. Street, D.M. Heisey, and O.L. Mangasarian. 
Computerized breast cancer diagnosis and prognosis from fine
needle aspirates.  
Archives of Surgery 1995;130:511-516.

W.H. Wolberg, W.N. Street, D.M. Heisey, and O.L. Mangasarian. 
Computer-derived nuclear features distinguish malignant from
benign breast cytology.  
Human Pathology, 26:792--796, 1995.
See also: http://www.cs.wisc.edu/~olvi/uwmp/mpml.html http://www.cs.wisc.edu/~olvi/uwmp/cancer.html

# Result :-

- predicting field 2, diagnosis: B = benign, M = malignant
- sets are linearly separable using all 30 input features
- best predictive accuracy obtained using one separating plane
    in the 3-D space of Worst Area, Worst Smoothness and
    Mean Texture.  Estimated accuracy 97.5% using repeated
    10-fold crossvalidations.  Classifier has correctly
    diagnosed 176 consecutive new patients as of November

# Conclusion :- 

Several of the papers listed above contain detailed descriptions of how these features are computed.

The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

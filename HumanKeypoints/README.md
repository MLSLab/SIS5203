# Human keypoints detection 


## OKS Evaluation
https://cocodataset.org/#download 에서 제공하는 2017 Train/Val annotations 를 사용.

* Image 정의 부분
이미지 index가 157928 일때, 

https://github.com/MLSLab/SIS5203/blob/babe3bfcab758b372a74c33a47c81eb64083be67/HumanKeypoints/person_keypoints_val2017_small2.json#L73-L82


* 해당 이미지의 첫번째 annotation (뒷부분)
https://github.com/MLSLab/SIS5203/blob/babe3bfcab758b372a74c33a47c81eb64083be67/HumanKeypoints/person_keypoints_val2017_small2.json#L465-L475

* 해당 이미지의 두번째 annotation (뒷부분)
https://github.com/MLSLab/SIS5203/blob/babe3bfcab758b372a74c33a47c81eb64083be67/HumanKeypoints/person_keypoints_val2017_small2.json#L597-L606




* OKS 관련


$$
OKS = \Sigma_{i}{[exp(\frac{-d^2_i}{2s^2k^2_i}\delta(v_i > 0)]/\Sigma_{i}[\delta(v_{i}>0)]}
$$


# References
* Original version : https://github.com/MLSLab/OKS-evaluation

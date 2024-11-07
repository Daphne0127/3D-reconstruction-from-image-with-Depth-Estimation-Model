# 3D-reconstruction-from-image-with-Depth-Estimation-Model
## Introduction
Depth estimation has long been essential in computer vision. Traditional 3D reconstruction pipelines, whether using multiple or single views, involve multiple steps where tasks operate independently, limiting information flow and mutual support. Depth sensors are also prone to issues with object material and reflectivity, causing missing data in areas like reflective surfaces.

Recently, deep learning has simplified depth estimation from images, as explored in works such as  "Repurposing Diffusion-Based Image Gen- erators for Monocular Depth Estimation","DUStR: Geometric 3D Vision Made Easy", "Grounding Image Matching in 3D with MASt3R" , "Depth Anything: Unleashing the Power of Large- Scale Unlabeled Data" and "Depth Anything v2". These models enable depth prediction from a single image, eliminating the need for camera parameters.

My research adapts these models for video sequences to reconstruct 3D scenes by integrating predicted depth with camera parameters. This approach aims to streamline traditional pipelines, achieving similar precision through deep learning.
## Method
![](DUSt3r/Method.jpg)
![](MASt3r/Method.jpg)
## Reference
- Yang, L., Kang, B., Huang, Z., Zhao, Z., Xu, X., Feng, J., Zhao, H. "Depth Anything V2." *arXiv preprint arXiv:2406.09414*, 2024.
- Yang, L., Kang, B., Huang, Z., Xu, X., Feng, J., Zhao, H. "Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data." *CVPR*, 2024.
- Leroy, V., Cabon, Y., Revaud, J. "Grounding Image Matching in 3D with MASt3R." *arXiv preprint arXiv:2406.09756*, 2024.
- Wang, S., Leroy, V., Cabon, Y., Chidlovskii, B., Revaud, J. "DUSt3R: Geometric 3D Vision Made Easy." *CVPR*, 2024.
- Ke, B., Obukhov, A., Huang, S., Metzger, N., Daudt, R. C., Schindler, K. "Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation." *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 2024.

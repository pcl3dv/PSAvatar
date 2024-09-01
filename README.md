<div align="center">

#  PSAvatar: A Point-based Shape Model for Real-Time Head Avatar Animation with 3D Gaussian Splatting
Zhongyuan Zhao<sup>1,2</sup> Zhenyu Bao<sup>1,2</sup>, Qing Li<sup>1</sup>, Guoping Qiu<sup>3,4</sup>, Kanglin Liu<sup>1,*</sup>

<sup>1</sup>Pengcheng Laboratory    <sup>2</sup>Peking University    <sup>3</sup>University of Nottingham    <sup>4</sup>Shenzhen University

<sup>*</sup>corresponding author: max.liu.426@gmail.com

### [Paper](https://arxiv.org/abs/2401.12900) | Project | [Video](https://github.com/user-attachments/assets/1d075705-11ac-43ee-a771-16f2d1621083) | Code ( is coming soon... )

</div>

https://github.com/user-attachments/assets/1d075705-11ac-43ee-a771-16f2d1621083

***Abstract**: 	Despite much progress, achieving real-time high-fidelity head avatar animation is still difficult and existing methods have to trade-off between speed and quality. 3DMM based methods often fail to model non-facial structures such as eyeglasses and hairstyles, while neural implicit models suffer from deformation inflexibility and rendering inefficiency. Although 3D Gaussian has been demonstrated to possess promising capability for geometry representation and radiance field reconstruction, applying 3D Gaussian in head avatar creation remains a major challenge since it is difficult for 3D Gaussian to model the head shape variations caused by changing poses and expressions. In this paper, we introduce PSAvatar, a novel framework for animatable head avatar creation that utilizes discrete geometric primitive to create a Point-based Shape Model (PSM) and employs 3D Gaussian for fine detail representation and high fidelity rendering. The PSM uses points instead of meshes for 3D representation to achieve enhanced representation flexibility. Specifically, PSM first converts the FLAME mesh to points by sampling on the surfaces as well as off the meshes to enable the reconstruction of not only surface-like structures but also complex geometries such as eyeglasses and hairstyles. By aligning these points with the head shape in an analysis-by-synthesis manner, the PSM makes it possible to utilize 3D Gaussian for fine detail representation and appearance modeling, thus enabling the creation of high-fidelity avatars. We show that PSAvatar can reconstruct high-fidelity head avatars of a variety of subjects and the avatars can be animated in real-time ($\ge$ 25 fps at a resolution of 512 $\times$  512 ).


## Animation Results
Tested on Nvidia RTX 3090.  Videos can be found at

https://github.com/pcl3dv/PSAvatar/blob/main/videos/subj1.mp4

https://github.com/pcl3dv/PSAvatar/blob/main/videos/multi-subjects.mp4

### driven by the pose, expression and camera parameters

https://github.com/pcl3dv/PSAvatar/assets/157086671/15916ce6-1768-4c6f-bc89-c4f8dc2421c7


### multi-identity animation
Four avatars are rendered at the same time, such an operation would decrease the frame rate.

https://github.com/pcl3dv/PSAvatar/assets/157086671/d49e3090-6e55-4d11-8e85-fa3737613b7d

### the effect of the enhancement operation

https://github.com/pcl3dv/PSAvatar/assets/157086671/e755c668-f8b0-4d4b-83a1-c5c16030dd55









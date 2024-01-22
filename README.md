<div align="center">

#  PSAvatar: A Point-based Morphable Shape Model for Real-Time Head Avatar Creation with 3D Gaussian Splatting
Zhongyuan Zhao<sup>1,2</sup> Zhenyu Bao<sup>1,2</sup>, Qing Li<sup>1</sup>, Guoping Qiu<sup>3,4</sup>, Kanglin Liu<sup>1,*</sup>

<sup>1</sup>Pengcheng Laboratory    <sup>2</sup>Peking University    <sup>3</sup>University of Nottingham    <sup>4</sup>Shenzhen University

<sup>*</sup>corresponding author: max.liu.426@gmail.com

</div>

<img src="https://github.com/pcl3dv/SplatAvatar/blob/main/images/fig1.jpg">

***Abstract**: Point and Gaussian splat show improved representation flexibility over 3D morphable models (3DMMs), and outperform implicit representation in terms of rendering efficiency.
	However, modeling the dynamics of human heads remains a major challenge for point and Gaussian splat due to the absence of the parametric morphable model as that in 3DMMs.
	To this end, we present SplatAvatar, a novel framework for creating head avatars that can be animated in real-time with given poses and expressions.
	Specifically, SplatAvatar  introduces the splat-based morphable shape model (Splat-MSM) for modeling the shape variation with poses and expressions. 
	To achieve this, Splat-MSM inherits the capability of being morphed from the parametric morphable model, and represents the geometry with point splats instead of meshes, enhancing the representation flexibility especially for complex volumetric structures. 
	Splat-MSM not only allows for modeling surface-like geometries, but also encourages reconstructing complex structures, e.g., diverse hair styles, complex accessories, etc..
	In addition, SplatAvatar employs Gaussian splats in combination with Splat-MSM for further improving the representation capability and modeling the appearance. 
	SplatAvatar gains improved representation flexibility over 3DMMs, and achieves real-time (>= 25 fps at the resolution of 512 $\times$ 512) rendering superior to implicit models.
	We conduct head avatar reconstruction on a variety of subjects, and implement real-time high-fidelity animation controlled by the morphable model parameters.
	Extensive experiments demonstrate that the introduced SplatAvatar outperforms the existing works.

Code is coming soon.

## Animation Results
Tested on Nvidia RTX 3090. Uncompressed videos can be found at

https://github.com/pcl3dv/SplatAvatar/blob/main/images/subj1.mp4

https://github.com/pcl3dv/SplatAvatar/blob/main/images/multi-id.mp4

### driven by the pose, expression and camera parameters

https://github.com/pcl3dv/SplatAvatar/assets/157086671/67680481-b998-4be8-b585-8d85a9b7fdd8



### multi-identity animation
Four avatars are rendered at the same time, such an operation would decrease the frame rate.

https://github.com/pcl3dv/SplatAvatar/assets/157086671/10ced56c-aaa5-42c0-95bc-75fb0f2b158a






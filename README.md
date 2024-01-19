<div align="center">

# <b>SplatAvatar</b>: Real-Time Animatable Head Avatar with Splat
Zhongyuan Zhao<sup>1,2</sup> Zhenyu Bao<sup>1,2</sup>, Guoping Qiu<sup>3,4</sup>, Qing Li<sup>1</sup>, Kanglin Liu<sup>1,*</sup>

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
	SplatAvatar gains improved representation flexibility over 3DMMs, and achieves real-time (>= 30fps at the resolution of 512 $\times$ 512) rendering superior to implicit models.
	We conduct head avatar reconstruction on a variety of subjects, and implement real-time high-fidelity animation controlled by the morphable model parameters.
	Extensive experiments demonstrate that the introduced SplatAvatar outperforms the existing works.

Code is coming soon.

## Animation Results
### driven by the pose, expression and camera parameters

https://github.com/pcl3dv/SplatAvatar/assets/157086671/cbec38d9-1556-47b0-a87e-5750a75872e6

### multi-identity animation



https://github.com/pcl3dv/SplatAvatar/assets/157086671/2c947fcf-78db-4e5d-b50b-70a93e50fbdd




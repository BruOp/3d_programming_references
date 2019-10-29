# References for Learning 3D Programming

A collection of useful resources I want to be able to reference in the future.

- [References for Learning 3D Programming](#references-for-learning-3d-programming)
  - [Compute Shaders](#compute-shaders)
    - [Blog Posts](#blog-posts)
  - [Gamma](#gamma)
    - [Blog Posts](#blog-posts-1)
  - [Image Based Lighting](#image-based-lighting)
    - [Papers](#papers)
  - [Post Processing (Motion Blur/DoF)](#post-processing-motion-blurdof)
    - [Papers](#papers-1)
    - [Blog Posts](#blog-posts-2)
    - [Presentations](#presentations)
  - [Physically Based Rendering](#physically-based-rendering)
    - [Blog Posts](#blog-posts-3)
    - [Papers](#papers-2)
    - [Presentations](#presentations-1)
    - [Examples](#examples)
  - [Shadows](#shadows)
    - [Blog Posts](#blog-posts-4)
    - [Examples](#examples-1)
    - [Presentations](#presentations-2)
  - [Temporal Anti-Aliasing](#temporal-anti-aliasing)
    - [Blog Posts](#blog-posts-5)
    - [Presentations](#presentations-3)
  - [Tone Mapping](#tone-mapping)
    - [Blog Posts](#blog-posts-6)
    - [Examples](#examples-2)
    - [Assets](#assets)
  - [HDR](#hdr)
    - [Blog Posts](#blog-posts-7)

## Compute Shaders

### Blog Posts

- [Introduction to compute shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/index.html) by Anteru

## Gamma

### Blog Posts

- [What Every Coder Should Know About Gamma](http://blog.johnnovak.net/2016/09/21/what-every-coder-should-know-about-gamma/) by John Novak

## Image Based Lighting

### Papers

- [A Multiple-scattering Microfacet Model for Real-time Image-based Lighting](http://www.jcgt.org/published/0008/01/03/paper.pdf) by Carmelo J. Fdez-Agüera

## Post Processing (Motion Blur/DoF)

### Papers

- [A Reconstruction Filter for Plausible Motion Blur](https://casual-effects.com/research/McGuire2012Blur/McGuire12Blur.pdf) by Morgan McGuire et al.
- [A Fast and Stable Feature-Aware Motion Blur Filter](https://casual-effects.com/research/Guertin2013MotionBlurReport/index.html) by Jean-Philippe Guertin et al.

### Blog Posts

- [Designing a next-generation post-effects pipeline](https://bartwronski.com/2014/12/09/designing-a-next-generation-post-effects-pipeline/) by Bart Wronski
- [Separable disk-like depth of field](https://bartwronski.com/2017/08/06/separable-bokeh/comment-page-1/) by Bart Wronski

### Presentations

- [Next Generation Post Processing In Call Of Duty: Advanced Warfare](https://advances.realtimerendering.com/s2014/) by Jorge Jimenez

## Physically Based Rendering

### Blog Posts

- [Notes on Importance Sampling](https://www.tobias-franke.eu/log/2014/03/30/notes_on_importance_sampling.html) by Tobias Franke
- [A multi-faceted exploration](https://blog.selfshadow.com/2018/06/04/multi-faceted-part-1/) by Stephen Hill
- [Sampling Microfacet Brdf](https://agraphicsguy.wordpress.com/2015/11/01/sampling-microfacet-brdf/) by A Graphics Guy
- [Importance Sampling techniques for GGX with Smith Masking-Shadowing: Part 1](https://schuttejoe.github.io/post/ggximportancesamplingpart1/)
- [GPU-Based Importance Sampling](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch20.html) by Křivánek and Colbert
- [How is the NDF really defined](http://www.reedbeta.com/blog/hows-the-ndf-really-defined/) by Nathan Reed

### Papers

- [Real shading in unreal engine 4](https://cdn2.unrealengine.com/Resources/files/2013SiggraphPresentationsNotes-26915738.pdf) by Brian Karis
- [Revisiting physically based shading at Imageworks](https://blog.selfshadow.com/publications/s2017-shading-course/imageworks/s2017_pbs_imageworks_slides_v2.pdf) by Kulla and Conty
- [Practical multiple scattering compensation for microfacet models](https://blog.selfshadow.com/publications/turquin/ms_comp_final.pdf) by Emmanuel Turquin
- [A Multiple-scattering Microfacet Model for Real-time Image-based Lighting](http://www.jcgt.org/published/0008/01/03/paper.pdf) by Carmelo J. Fdez-Agüera
- [PBR Diffuse Lighting for GGX + Smith Microsurfaces](https://twvideo01.ubm-us.net/o1/vault/gdc2017/Presentations/Hammon_Earl_PBR_Diffuse_Lighting.pdf) by Earl Hammon
- [Microfacet Models for Refraction through Rough Surfaces](http://www.cs.cornell.edu/~srm/publications/EGSR07-btdf.pdf) by Walter et al.
- [Multiple-Scattering Microfacet BSDFs with the Smith Model](https://eheitzresearch.wordpress.com/240-2/) by Eric Heitz et al
- [Real-Time Polygonal-Light Shading with Linearly Transformed Cosines](https://eheitzresearch.wordpress.com/415-2/) by Erir Heitz et al.

### Presentations

- [Background: Physics and Math of Shading](https://blog.selfshadow.com/publications/s2013-shading-course/hoffman/s2013_pbs_physics_math_slides.pdf) by Naty Hoffman
- [A Journey Through Implementing Multiscattering BRDFs and Area Lights](http://advances.realtimerendering.com/s2019/index.htm) by Stephen McAuley et al

### Examples

- [Moving Frostbite to PBR](https://seblagarde.files.wordpress.com/2015/07/course_notes_moving_frostbite_to_pbr_v32.pdf) by Sebastian Legarde et al
- [Filament](https://google.github.io/filament/Filament.html) by Romain Guy et al of Google

## Shadows

### Blog Posts

- [Shadow Mapping Summary – Part 1](http://the-witness.net/news/2013/09/shadow-mapping-summary-part-1/) by Ignacio Castaño
- [A Sampling of Shadow Techniques](https://mynameismjp.wordpress.com/2013/09/10/shadow-maps/) by Matt Pettineo
- [Common Techniques to Improve Shadow Depth Maps](https://docs.microsoft.com/en-us/windows/win32/dxtecharts/common-techniques-to-improve-shadow-depth-maps)

### Examples

- [Shadows](https://github.com/TheRealMJP/Shadows) by Matt Pettineo

### Presentations

- [Playing with Real-Time Shadows](https://www.realtimeshadows.com/sites/default/files/Playing%20with%20Real-Time%20Shadows_0.pdf) by Nikolas Kasyan

## Temporal Anti-Aliasing

### Blog Posts

- [Temporal supersampling and antialiasing](https://bartwronski.com/2014/03/15/temporal-supersampling-and-antialiasing/) by Bart Wronski
- [Temporal supersampling pt. 2 – SSAO demonstration](https://bartwronski.com/2014/04/27/temporal-supersampling-pt-2-ssao-demonstration/) by Bart Wronski

### Presentations

- [Graphics Gems from CRYENGINE 3](https://advances.realtimerendering.com/s2013/index.html) by Tiago Sousa
- [High-Quality Temporal Supersampling](https://advances.realtimerendering.com/s2014/) by Brian Karis
- [Temporal Antialiasing in Uncharted 4](https://advances.realtimerendering.com/s2016/index.html) by Ke Xu
- [Filmic SMAA: Sharp Morphological and Temporal Antialiasing](https://advances.realtimerendering.com/s2016/index.html) by Jorge Jimenez

## Tone Mapping

### Blog Posts

- [HDR color grading and display in Frostbite](https://www.ea.com/frostbite/news/high-dynamic-range-color-grading-and-display-in-frostbite) by Alex Fry
- [Filmic Tonemapping with Piecewise Power Curves](http://filmicworlds.com/blog/filmic-tonemapping-with-piecewise-power-curves/) by John Hable
- [Automatic Exposure](https://knarkowicz.wordpress.com/2016/01/09/automatic-exposure/) by Krzysztof Narkowicz
- [A Closer Look at Tone Mapping](https://mynameismjp.wordpress.com/2010/04/30/a-closer-look-at-tone-mapping/) by Matt Pettineo
- [Artist Friendly HDR With Exposure Values](http://www.reedbeta.com/blog/artist-friendly-hdr-with-exposure-values/) by Nathan Reed
- [Photographic Tone Reproduction for Digital Images](http://www.cs.utah.edu/~reinhard/cdrom/tonemap.pdf) by Reinhard et al
- [Localized tonemapping – is global exposure and global tonemapping operator enough for video games?](https://bartwronski.com/2016/08/29/localized-tonemapping/) by Bart Wronski
- [Adaptive Exposure from Luminance Histograms](http://alextardif.com/HistogramLuminance.html) by Alex Tardif

### Examples

- [Tonemap Operators](https://www.shadertoy.com/view/llXyWr) by Romain Guy

### Assets

- [High-Resolution Light Probe Image Gallery ](http://gl.ict.usc.edu/Data/HighResProbes/) from Vision & Graphics Lab
- [sIBL Archive](http://www.hdrlabs.com/sibl/archive.html)

## HDR

### Blog Posts

- [HDR color grading and display in Frostbite](https://www.ea.com/frostbite/news/high-dynamic-range-color-grading-and-display-in-frostbite) by Alex Fry
- [HDR Display – First Steps](https://knarkowicz.wordpress.com/2016/08/31/hdr-display-first-steps/) by Krzysztof Narkowicz
- [Tonemapping on HDR displays. ACES to rule ‘em all? ](https://c0de517e.blogspot.com/2017/02/tonemapping-on-hdr-displays-aces-to.html) by Angelo Pesce

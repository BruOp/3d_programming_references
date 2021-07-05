# References for Learning 3D Programming

A collection of useful resources I want to be able to reference in the future.

- [References for Learning 3D Programming](#references-for-learning-3d-programming)
  - [Anti-Aliasing](#anti-aliasing)
    - [Blog Posts](#blog-posts)
    - [Papers](#papers)
  - [Clustered Shadering](#clustered-shadering)
    - [Blog Posts](#blog-posts-1)
    - [Papers](#papers-1)
    - [Presentations](#presentations)
  - [Compute Shaders](#compute-shaders)
    - [Blog Posts](#blog-posts-2)
  - [Culling](#culling)
    - [Presentations](#presentations-1)
    - [Blog Posts](#blog-posts-3)
  - [Gamma](#gamma)
    - [Blog Posts](#blog-posts-4)
  - [Image Based Lighting](#image-based-lighting)
    - [Papers](#papers-2)
  - [Normal Mapping and Specular Aliasing](#normal-mapping-and-specular-aliasing)
    - [Blog Posts](#blog-posts-5)
    - [Papers](#papers-3)
    - [Presentations](#presentations-2)
    - [Examples](#examples)
  - [Post Processing (Motion Blur/DoF)](#post-processing-motion-blurdof)
    - [Papers](#papers-4)
    - [Blog Posts](#blog-posts-6)
    - [Presentations](#presentations-3)
  - [Physically Based Rendering](#physically-based-rendering)
    - [Blog Posts](#blog-posts-7)
    - [Papers](#papers-5)
    - [Presentations](#presentations-4)
    - [Examples](#examples-1)
  - [Shadows](#shadows)
    - [Blog Posts](#blog-posts-8)
    - [Examples](#examples-2)
    - [Presentations](#presentations-5)
  - [Temporal Anti-Aliasing](#temporal-anti-aliasing)
    - [Blog Posts](#blog-posts-9)
    - [Presentations](#presentations-6)
  - [Tone Mapping](#tone-mapping)
    - [Blog Posts](#blog-posts-10)
    - [Examples](#examples-3)
    - [Assets](#assets)
  - [HDR](#hdr)
    - [Blog Posts](#blog-posts-11)
  - [Volumetric Effects](#volumetric-effects)
    - [Blog Posts](#blog-posts-12)
    - [Papers](#papers-6)
    - [Presentations](#presentations-7)
    - [Examples/Code](#examplescode)

## Anti-Aliasing

### Blog Posts

- [Anti-Aliasing (SMAA T2X)](http://marcel-schindler.weebly.com/blog/anti-aliasing-smaa-t2x) by Marcel Schindler

### Papers

- [SMAA](http://www.iryoku.com/smaa/) by Jimenez et al.

## Clustered Shadering

### Blog Posts

- [Bindless Texturing for Deferred Rendering and Decals](https://therealmjp.github.io/posts/bindless-texturing-for-deferred-rendering-and-decals/) by Matt J. Pettineo
- [Clustered shading evolution in Granite](https://themaister.net/blog/2020/01/10/clustered-shading-evolution-in-granite/) by Hans Kristian
- [Cull that Cone!](https://bartwronski.com/2017/04/13/cull-that-cone/) by Bart Wronski
- [A Primer On Efficient Rendering Algorithms & Clustered Shading](www.aortiz.me/2018/12/21/CG.html) by Ángel Ortiz

### Papers

- [Clustered Deferred and Forward Shading](http://www.klayge.org/material/4_4/Tiled/clustered_shading_preprint.pdf) by Ola Olsson, Markus Billeter, and Ulf Assarsson

### Presentations

- [Improved Culling for Tiled and Clustered Rendering](http://advances.realtimerendering.com/s2017/2017_Sig_Improved_Culling_final.pdf) by Michal Drobot
- [Practical Clustered Shading](http://newq.net/dl/pub/SA2014Practical.pdf) by Emil Persson
- [Rendering The Hellscape of Doom: Eternal](http://advances.realtimerendering.com/s2020/RenderingDoomEternal.pdf) by Jean Geffroy, Axel Gneiting, and Yixin Wang
- [The Devil is in the Details](http://advances.realtimerendering.com/s2016/Siggraph2016_idTech6.pdf) by Tiago Sousa and Jean Geffroy

## Compute Shaders

### Blog Posts

- [Introduction to compute shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/index.html) by Anteru

## Culling

### Presentations

- [Culling the Battlefield](https://www.slideshare.net/DICEStudio/culling-the-battlefield-data-oriented-design-in-practice) by Daniel Collin
- [GPU-Driven Rendering Pipelines](http://advances.realtimerendering.com/s2015/aaltonenhaar_siggraph2015_combined_final_footer_220dpi.pdf)  by Ulrich Haar and Sebastian Aaltonen
- [Optimizing the Graphics Pipeline with Compute](https://www.wihlidal.com/projects/fb-gdc16/) by Graham Wihlidal

### Blog Posts

- [Software Occlusion Culling](https://software.intel.com/content/www/us/en/develop/articles/software-occlusion-culling.html) by Kiefer Kuah
- [Experiments in GPU Base Occlusion Culling](https://interplayoflight.wordpress.com/2017/11/15/experiments-in-gpu-based-occlusion-culling/) by Kostas Anagnostou
- [Twitter Thread on Culling](https://twitter.com/SebAaltonen/status/1300062590219976704?s=20)

## Gamma

### Blog Posts

- [What Every Coder Should Know About Gamma](http://blog.johnnovak.net/2016/09/21/what-every-coder-should-know-about-gamma/) by John Novak

## Image Based Lighting

### Papers

- [A Multiple-scattering Microfacet Model for Real-time Image-based Lighting](http://www.jcgt.org/published/0008/01/03/paper.pdf) by Carmelo J. Fdez-Agüera

## Normal Mapping and Specular Aliasing

### Blog Posts

- [Specular Showdown](https://blog.selfshadow.com/2011/07/22/specular-showdown/) by Stephen Hill
- [Twitter Thread on TAA and Specular Aliasing](https://twitter.com/js_guay/status/1196250241869209601?s=20)

### Papers

- [LEAN Mapping](https://www.csee.umbc.edu/~olano/papers/lean/) by Marc Olano and Dan Baker
- [Improved Specular AA](<https://www.jp.square-enix.com/tech/library/pdf/ImprovedGeometricSpecularAA(slides).pdf>) by Tokuyoshi and Kaplanyan

### Presentations

- [Advanced VR Rendering](http://media.steampowered.com/apps/valve/2015/Alex_Vlachos_Advanced_VR_Rendering_GDC2015.pdf) by Alex Vlachos [(Video)](https://archive.org/details/GDC2015Vlachos)

### Examples

- [Specular AA Example](https://blog.selfshadow.com/sandbox/specaa.html) by Anton Kaplanyan

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

## Volumetric Effects

### Blog Posts

- [Sébastien Hillaire's personal website](https://sebh.github.io/)
- [Rendering volumetric Clouds Using Signed Distance Fields](https://blog.uhawkvr.com/rendering/rendering-volumetric-clouds-using-signed-distance-fields/) by Felix Westin

### Papers

- [A Scalable and Production ReadySky and Atmosphere Rendering Technique](https://sebh.github.io/publications/egsr2020.pdf) by Sébastien Hillaire
- [Precomputed Atmospheric Scattering](https://ebruneton.github.io/precomputed_atmospheric_scattering/) by Eric Bruneton

### Presentations

- [Nubis: Authoring Real-Time Volumetric Cloudscapes with the Decima Engine](http://advances.realtimerendering.com/s2017/index.html) by Andrew Schneider
- [Physically Based and Scalable Atmospheres in Unreal Engine](https://blog.selfshadow.com/publications/s2020-shading-course/hillaire/s2020_pbs_hillaire_slides.pdf) by Sébastien Hillaire
- [Physically-based and Unified Volumetric Rendering in Frostbite](https://www.ea.com/frostbite/news/physically-based-unified-volumetric-rendering-in-frostbite) by Sébastien Hillaire
- [Physically Based Sky, Atmosphere & Cloud Rendering](https://www.ea.com/frostbite/news/physically-based-sky-atmosphere-and-cloud-rendering) by Sébastien Hillaire

### Examples/Code

- [Tileable Volume Noise](https://github.com/sebh/TileableVolumeNoise) from Sébastien Hillaire for creating tileable noise textures for use in cloud rendering
- [Unreal Engine Sky Atmosphere Rendering Technique](https://github.com/sebh/UnrealEngineSkyAtmosphere) from Sébastien Hillaire, example of his ESGR 2020 paper algorithm

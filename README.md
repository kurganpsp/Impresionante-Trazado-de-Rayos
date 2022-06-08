# Impresionante Trazado de Rayos [![CC0 License](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

Una lista seleccionada de recursos sobre Trazado de Rayos. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Recursive_raytrace_of_a_sphere.png/240px-Recursive_raytrace_of_a_sphere.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Glasses_800_edit.png/320px-Glasses_800_edit.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Ray-traced_steel_balls.jpg/320px-Ray-traced_steel_balls.jpg" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Global_illumination.JPG" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/c/cb/Alexexterior2.jpg" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Path_tracing_001.png/240px-Path_tracing_001.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Glass_ochem.png/640px-Glass_ochem.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Glas-1000-enery.jpg/320px-Glas-1000-enery.jpg" height="200">

## Table of Contents

- [Glossary of Terms](GLOSSARY.md)
- [What is Ray Tracing?](#what-is-ray-tracing)
- [Ray Marching](#ray-marching)
- [Iconic Publications](#iconic-publications)
- [Path Tracing](#path-tracing)
- [Photon Mapping](#photon-mapping)
- [Math](#math)
- [Ray Casting](#ray-casting)
- [BxDF](#bxdf)
- [Sampling Methods](#sampling-methods)
- [Denoising, Filtering, and Reconstruction](#denoising-filtering-and-reconstruction)
- [Realtime](#realtime)
- [Reference Scenes](#reference-scenes)
- [News](#news)
- [API's](#apis)
  - [Vulkan Ray Tracing](#vulkan-ray-tracing)
  - [Nvidia RTX](#nvidia-rtx)
  - [Microsoft DirectX Raytracing (RTX)](#microsoft-directx-raytracing-dxr)
  - [Nvidia OptiX](#nvidia-optix)
  
## Legend

| Icon | Meaning |
| ---- | ------- |
| 📖 | Reading |
| 📺 | Video |
| 💾 | Code / Asset |

---

## [Glossary of Terms](GLOSSARY.md)

## What is Ray Tracing?

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ray_trace_diagram.svg/320px-Ray_trace_diagram.svg.png" height="200">

- 📺 [(2020) - Ray Tracing Essentials - Eric Haines ](https://www.youtube.com/playlist?list=PL5B692fm6--sgm8Uiava0IIvUojjFOCSR)
- 📺 [(2019) - An Explanation of the Rendering Equation - Eric Arnebäck](https://www.youtube.com/watch?v=eo_MTI-d28s)
- 📖 [(2018) - Physically Based Rendering Book (PBR) - Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann](http://www.pbr-book.org/)
- 📖 [(2018) - What’s the Difference Between Ray Tracing and Rasterization? - *Brian Caulfield*](https://blogs.nvidia.com/blog/2018/03/19/whats-difference-between-ray-tracing-rasterization/)
- 📖 [(2018) - Ray Tracing Resources Page - Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire](http://www.realtimerendering.com/raytracing.html)
- 📺 [(2017) - Rendering / Ray Tracing Course - TU Wien](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi)
- 📺 [(2016) - Disney's Practical Guide to Path Tracing - *Disney*](https://youtu.be/frLwRLS_ZR0)
- 📖 [(2016) - Ray Tracing in One Weekend - *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
- 📖 [(2016) - Ray Tracing: The Next Week - *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-second-weekend.html)
- 📖 [(2016) - Ray Tracing: The Rest of Your Life - *Peter Shirley*](http://in1weekend.blogspot.com/2016/03/ray-tracing-rest-of-your-life.html)
- 📖 [(1991) - An Introduction to Ray Tracing - *Andrew Glassner*](http://www.realtimerendering.com/raytracing/An-Introduction-to-Ray-Tracing-The-Morgan-Kaufmann-Series-in-Computer-Graphics-.pdf)



## Ray Marching

- 💾 [Nathan Vaughn/⭐/  Shadertoy Series](https://inspirnathan.com/posts/47-shadertoy-tutorial-part-1/)
- 💾 [Martijn Steinrucken/⭐/ Ray Marching for Dummies!](https://www.youtube.com/watch?v=PGtv-dBi2wE)
- 💾 [Michael Walczyk/⭐/ Ray Marching](https://michaelwalczyk.com/blog-ray-marching.html)



## Iconic Publications

- 📖 [(2003) - Global Illumination Compendium - *Philip Dutré*](https://people.cs.kuleuven.be/~philip.dutre/GI/TotalCompendium.pdf)
- 📖 [(1998) - Robust Monte Carlo Methods for Light Transport Simulation  - Eric Veach](https://graphics.stanford.edu/papers/veach_thesis/)
- 📖 [(1986) - The Rendering Equation - James T. Kajiya](http://www.dca.fee.unicamp.br/~leopini/DISCIPLINAS/IA725/ia725-12010/kajiya-SIG86-p143.pdf)
- 📖 [(1979) - An Improved Illumination Model for Shaded Display -  J.D. Foley and Turner Whitted*](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.156.1534)
- 📖 [(1968) - Some Techniques for Shading Machine Renderings of Solids - *Arthur Appel*](http://graphics.stanford.edu/courses/Appel.pdf)


## Path Tracing

- 📖 [(2018) - Path Tracing in Production - *Luca Fascione, Johannes Hanika, Rob Pieké, Ryusuke Villemin, Christophe Hery, Manuel Gamito, Luke Emrose, and André Mazzone*](https://jo.dreggn.org/path-tracing-in-production/2018/index.html)
- 📖 [(2018) - Path Tracing Coherency - *Anders Lindqvist*](https://www.breakin.se/learn/pathtracing-coherency.html)
- 📖 [(2018) - Path Traced Depth of Field and Bokeh - *Alan Wolfe*](https://blog.demofox.org/2018/07/04/pathtraced-depth-of-field-bokeh/)
- 📖 [(2018) - Daily Path Tracer - *Aras Pranckevičius*](http://aras-p.info/blog/2018/03/28/Daily-Pathtracer-Part-0-Intro/)
- 📖 [(2017) - Path Tracing - *Fabio Pellacini and Steve Marschner*](http://pellacini.di.uniroma1.it/teaching/graphics17b/lectures/12_pathtracing.pdf)
- 📖 [(2017) - Microfacet-based Normal Mapping for Robust Monte Carlo Path Tracing - *Vincent Schüssler, Eric Heitz, Johannes Hanika, Carsten Dachsbacher*](https://jo.dreggn.org/home/2017_normalmap.pdf)

## Photon Mapping

- 📖 [(2001) - Photon Mapping - *Zack Waters*](https://web.cs.wpi.edu/~emmanuel/courses/cs563/write_ups/zackw/photon_mapping/PhotonMapping.html)

## Math

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Inner-product-angle.svg/320px-Inner-product-angle.svg.png" height="200">

- 📺 [(2022) - Linear Algebra - *Khan Academy*](https://www.khanacademy.org/math/linear-algebra)
- 📖 [(2018) - PBRT Chapter 2 Geometry and Transformations - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Geometry_and_Transformations.html)
- 📖 [(2018) - PBRT Chapter 3 Shapes - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Shapes.html)
- 📖 [(2015) - Immersive Math - Linear Algebra - *J. Ström, K. Åström, and T. Akenine-Möller*](http://immersivemath.com/ila/index.html)

## Ray Casting

<img src="https://upload.wikimedia.org/wikipedia/commons/6/6c/Ray_triangle.png" height="150"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Example_of_bounding_volume_hierarchy.svg/320px-Example_of_bounding_volume_hierarchy.svg.png" height="150">

- 📖 [(2022) - Ray-Triangle Intersection: Geometric Solution - *Scratchapixel*](https://www.scratchapixel.com/lessons/3d-basic-rendering/ray-tracing-rendering-a-triangle/ray-triangle-intersection-geometric-solution)
- 📖 [(2019) - Realtime Rendering Object/Object Intersection Page - *Eric Haines*](http://www.realtimerendering.com/intersections.html)
- 📖 [Introduction to Acceleration Structures - *Scratchapixel*](https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume)
- 📖 [(2019) - Dynamic BVH - *Erin Catto*](https://box2d.org/files/ErinCatto_DynamicBVH_Full.pdf)
- 📖 [(2018) - PBRT Chater 4 Primitives and Intersection Acceleration - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Primitives_and_Intersection_Acceleration.html)
- 📺 [How to Make 3D Fractals](https://www.youtube.com/watch?v=svLzmFuSBhk)
- 📖 [(1998) - ERIT: A Collection of Efficient and Reliable Intersection Tests - *Martin Held*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.49.9172&rep=rep1&type=pdf)


## BxDF

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d8/BSDF05_800.png" height="200">

- 📖 [(2018) - PBRT Chapter 5.6 Surface Reflection - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Color_and_Radiometry/Surface_Reflection.html)
- 📖 [(2018) - PBRT Chapter 8 Reflection Models - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Reflection_Models.html)
- 📖 [(2018) - PBRT Chapter 9 Materials - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Materials.html)
- 📖 [(2018) - PBRT Chapter 11 Volume Scattering - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Volume_Scattering.html)
- 📖 [(2018) - A Multifaceted Explanation Part 1 - *Stephen Hill*](https://blog.selfshadow.com/2018/05/13/multi-faceted-part-1/)
- 📖 [(2018) - A Multifaceted Explanation Part 2 - *Stephen Hill*](https://blog.selfshadow.com/2018/06/04/multi-faceted-part-2/)
- 📖 [(2018) - A Multifaceted Explanation Part 3 - *Stephen Hill*](https://blog.selfshadow.com/2018/08/05/multi-faceted-part-3/)
- 📖 [(2017) - Revisiting Physically Based Shading in ImageWorks - *Christopher Kulla & Alejandro Conty*](https://blog.selfshadow.com/publications/s2017-shading-course/imageworks/s2017_pbs_imageworks_slides.pdf)
- 📖 [(2016) - Physically Based Sky, Atmosphere, and Cloud Rendering in Frostbite - *Sebastien Hillaire*](https://media.contentapi.ea.com/content/dam/eacom/frostbite/files/s2016-pbs-frostbite-sky-clouds-new.pdf)
- 📺 [(2013) - Geometric Optics Playlist - *Doc Schuster*](https://www.youtube.com/playlist?list=PLLUpvzaZLf3IB4GEhaCg7L3ioiLkHLk7Q)


## Sampling Methods

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Hammersley_set_2D.svg/289px-Hammersley_set_2D.svg.png" height="200">

- 📖 [(2018) - PBRT Chapter 7 - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Sampling_and_Reconstruction.html)
- 📖 [(2018) - Generating Random Points in a Sphere - *Karthik Karanth*](https://karthikkaranth.me/blog/generating-random-points-in-a-sphere/)
- 📖 [(2018) - Flavors of Sampling in Ray Tracing  - *Peter Shirley*](http://psgraphics.blogspot.com/2018/10/flavors-of-sampling-in-ray-tracing.html)
- 📺 [(2020) - Continuous Multiple Importance Sampling - SIGGRAPH 2020 - *Rex West, Iliyan Georgiev , Adrien Gruson , Toshiya Hachisuka*](https://youtu.be/dxFSwplfdpk)
- 📖 [(2018) - Position-Free Monte Carlo Simulation for Arbitrary Layered BSDFs - *Yu Guo, Miloš Hašan, Shuang Zhao*](https://shuangz.com/projects/layered-sa18/)
- 📖 [Monte Carlo Integration - *Anders Lindqvist*](https://www.breakin.se/mc-intro/)
- 📖 [(2018) - Monte Carlo Integration Explanation in 1D - *Alan Wolfe*](https://blog.demofox.org/2018/06/12/monte-carlo-integration-explanation-in-1d/)
- 📖 [(2018) - Importance Sampling techniques for GGX with Smith Masking-Shadowing Part 1 - *Joe Schutte*](https://schuttejoe.github.io/post/ggximportancesamplingpart1/)
  - 📖 [(2018) - Importance Sampling techniques for GGX with Smith Masking-Shadowing Part 2 - *Joe Schutte*](https://schuttejoe.github.io/post/ggximportancesamplingpart2/)
- 📖 [(2018) - Double Hierarchies for Directional Importance Sampling in Monte Carlo Rendering - *Norbert Bus and Tamy Boubekeur*](http://www.jcgt.org/published/0006/03/02/)
- 📖 [(2018) - Importance Sampling of Many Lights with Adaptive Tree Splitting - *Alejandro Conty and Christopher Kulla*](http://aconty.com/pdf/many-lights-hpg2018.pdf)
- 📖 [(2018) - Monte Carlo Methods for Volumetric Light Transport Simulation - *Jan Novák, Iliyan Georgiev, Johannes Hanika, and Wojciech Jarosz*](http://iliyan.com/publications/VolumeSTAR)
- 📖 [(1998) - Robust Monte Carlo Methods Chapters 2, 9, & 11 - *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)


## Denoising, Filtering, and Reconstruction

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f4/Noise_salt_and_pepper.png" height="200">

- 📺 [(2018) - RTX Coffee Break: Ray Tracing and Denoising - *Edward Lu*](https://news.developer.nvidia.com/rtx-coffee-break-ray-tracing-and-denoising/)
- 📺 [(2018) - RTX Coffee Break: Ray Traced Reflections and Denoising - *Edward Lu*](https://news.developer.nvidia.com/rtx-coffee-break-ray-traced-reflections-and-denoising-952-minutes/)
- 📖 [(2017) - Spatiotemporal Variance-Guided Filtering: Real-Time Reconstruction for Path-Traced Global Illumination - *Christoph Schied, Anton Kaplanyan, Chris Wyman, Anjul Patney, Chakravarty R. Alla Chaitanya, John Burgess, Shiqiu Liu, Carsten Dachsbacher, Aaron Lefohn, Marco Salvi*](http://cg.ivd.kit.edu/svgf.php)
- 📖 [(2008) - Multidimensional Adaptive Sampling and Reconstruction for Ray Tracing - *Toshiya Hachisuka, Wojciech Jarosz, Richard Peter Weistroffer, Kevin Dale, Greg Humphreys, Matthias Zwicker, and Henrik Wann Jensen*](http://graphics.ucsd.edu/~henrik/papers/multidimensional_adaptive_sampling/)

## Realtime

- 📖 [(2018) - Real-Time Rendering Chapter - *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/Real-Time_Rendering_4th-Real-Time_Ray_Tracing.pdf)
- 📺 [(2018) - Real-Time Raytracing for Interactive Global Illumination Workflows in Frostbite / Shiny Pixels and Beyond: Real-Time Raytracing at SEED - *Sébastien Hillaire, Johan Andersson, and Colin Barré-Brisebois*](https://youtu.be/rhlGBCSv02M)
- 📖 [(2018) - Real-Time Ray Tracing of Correct* Soft Shadows - *Stephen Hill and Morgan McGuire*](http://advances.realtimerendering.com/s2018/s2018_real_time_correct_soft_shadows.pdf)
- 📺 [(2018) - Stochastic All the Things: Raytracing in Hybrid Real-Time Rendering - *Tomasz Stachowiak*](https://www.ea.com/seed/news/seed-dd18-presentation-slides-raytracing)
- 📖 [(2018) - Adopting Lessons From Offline Ray-Tracing to Real-Time Ray-Tracing for Practical Pipelines - *Matt Pharr*](http://advances.realtimerendering.com/s2018/Pharr%20-%20Advances%20in%20RTR%20-%20Real-time%20Ray%20Tracing.pdf)
- 📖 [(2018) - Game Ray Tracing: State-of-the-Art and Open Problems - *Colin Barré Brisebois*](https://www.ea.com/seed/news/hpg-2018-keynote)
- 💾 [Sol-R, an Open-Source CUDA/OpenCL Speed Of Light Ray-tracer](https://github.com/favreau/Sol-R)

## Reference Scenes

<img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Cornell_box.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Stanford_Bunny.stl/320px-Stanford_Bunny.stl.png" height="200">

- 💾 [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html)
- 💾 [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
- 💾 [PBRT Scenes v3](https://www.pbrt.org/scenes-v3.html)
- 💾 [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca)
- 💾 [Disney Data Sets](https://www.disneyanimation.com/data-sets/)

## News

- 📖 [Graphics Programming Weekly - *Jendrik Illner*](https://www.jendrikillner.com/post/)

## API's

- [Vulkan Ray Tracing](https://www.khronos.org/blog/ray-tracing-in-vulkan)
- [Nvidia RTX](https://developer.nvidia.com/rtx)
- [Microsoft DirectX Raytracing (DXR)](https://blogs.msdn.microsoft.com/directx/2018/03/19/announcing-microsoft-directx-raytracing/)
- [Nvidia OptiX](https://developer.nvidia.com/optix)
- [AMD Radeon-Rays](https://gpuopen.com/radeon-rays/)
- [Intel Embree](http://embree.github.io/)

### Vulkan Ray Tracing

- 📖 [(2020) - Ray Tracing In Vulkan - *Khronos*](https://www.khronos.org/blog/ray-tracing-in-vulkan)
- 📖 [(2020) - Vulkan Ray Tracing Tutorials - *Nvidia*](https://github.com/nvpro-samples/vk_raytracing_tutorial_KHR)

### Nvidia RTX

- 📖 [(2018) - NVIDIA Vulkan Ray Tracing Tutorial - *NVidia*](https://developer.nvidia.com/rtx/raytracing/vkray)
- 📖 [(2018) - Introduction to Real-Time Ray Tracing with Vulkan - *Nuno Subtil*](https://devblogs.nvidia.com/vulkan-raytracing/)
- 📖 [(2018) - Vulkan Raytracing Tutorials - *iOrange*](https://iorange.github.io/p02/TeapotAndBunny.html)
- 📺 [(2018) - Video Series: Practical Real-Time Ray Tracing With RTX - *Nvidia*](https://devblogs.nvidia.com/practical-real-time-ray-tracing-rtx/)
- 📖 [(2018) - Effectively Integrating RTX Ray Tracing into a Real-Time Rendering Engine - *Juha Sjoholm*](https://devblogs.nvidia.com/effectively-integrating-rtx-ray-tracing-real-time-rendering-engine/)

### Microsoft DirectX Raytracing (DXR)

- 📺📖 [(2018) - Introducion to DirectX Raytracing - *Chris Wyman, Shawn Hargreaves, Peter Shirley, Colin Barré-Brisebois*](http://intro-to-dxr.cwyman.org/)
- 📖 [(2018) - DX12 Ray Tracing Tutorials - *Martin-Karl Lefrançois and Pascal Gautron*](https://news.developer.nvidia.com/dx12-raytracing-tutorials/)
- 💾 [DXRPathTracer](https://github.com/TheRealMJP/DXRPathTracer)
- 📺 [(2018) - Real-Time Ray Tracing for Interactive Global Illumination Workflows in Frostbite - *Sebastien Hillaire, Charles de Rousiers, Diede Apers and Petter Edblom*](https://devblogs.nvidia.com/video-real-time-ray-tracing-workflows-frostbite/)

### Nvidia OptiX

- 📖 [(2019) - Ray Tracing The Rest of Your Life in OptiX - *João Vítor Silva*](https://joaovbs96.github.io/posts/rest-life/)
- 📖 [(2018) - OptiX QuickStart - *Nvidia*](https://docs.nvidia.com/gameworks/content/gameworkslibrary/optix/optix_quickstart.htm)
- 📖 [(2018) - Ray Tracing The Next Week in OptiX - *João Vítor Silva*](https://joaovbs96.github.io/posts/next-week/)
- 💾 [(2018) - optix_advanced_samples - *Nvidia*](https://github.com/nvpro-samples/optix_advanced_samples)
- 📺 [(2018) - GPU Ray Tracing for Film and Design: High Performance Ray Tracing with OptiX - *Oliver Klehm*](http://on-demand.gputechconf.com/siggraph/2018/video/sig1812-2-oliver-klehm-high-performance-optix.html)
- 📖 [(2017) - Introduction to OptiX - *Nvidia*](http://on-demand.gputechconf.com/gtc/2017/presentation/s7455-martin-stich-optix.pdf)


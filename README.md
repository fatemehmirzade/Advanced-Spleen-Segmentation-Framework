# Unet-model-for-spleen-segmentation

This study focused on the application of ultrasound imaging data acquired from patients' spleens, with the prime objective of applying computational algorithms for segmentation, identification, and precise localization of the spleen regions within the images. Such delineation facilitates subsequent quantitative assessments, notably the estimation of spleen dimensions, thereby potentially serving as an adjunctive diagnostic tool for discerning pathologic conditions such as infection.

For example, the Unet network architecture is selected here as the core computational framework in view of its established effectiveness in medical image analysis, more specifically in applications requiring high-fidelity delineation of anatomical structures. In more detail, the Unet architecture is realized through an encoder-decoder paradigm augmented with skip connections that enable the model to effectively capture both global context and fine-grained details within the images.

Empirical evaluation of the implemented Unet model demonstrates favorable performance characteristics, as evidenced by attained metrics. Specifically, examination of model performance on a distinct test dataset reveals a commendable accuracy metric of 0.91, indicative of the model's proficiency in accurately segmenting spleen regions within ultrasound images. Such outcomes underscore the utility and efficacy of the Unet network architecture in the context of medical image segmentation tasks, thereby affirming its suitability for the present application.
![plots](https://github.com/fmirzadeh99/Unet-model-for-spleen-segmentation/assets/169579231/cf519628-8fe9-4f38-be4b-66a3b10cf3db)

![image](https://github.com/fmirzadeh99/Unet-model-for-spleen-segmentation/assets/169579231/c60ebff6-74c2-4aeb-93ad-86a388f38bb5)

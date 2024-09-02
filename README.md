# DiffSynFace
![DiffSynFace photos](https://github.com/user-attachments/assets/00ef6082-25a5-46ca-81ad-809a74dfb5ae)

## Overview
### Dataset Description

DiffSynFace is a dataset consists of synthetic human face images generated using state-of-the-art Diffusion Model-based generative AI tools. This dataset consists of 40k+ synthetic facial images generated across diverse demographics to ensure balanced representation. We include six ethnicity groups: **African, American, East Asian, European, Indian,** and **South Asian**; two genders: **Female** and **Male**; and four age groups: **20s, 30s, 40s,** and **50s**. Each age group is further divided into three stages: **'early', 'mid',** and **'late'**, resulting in an equal number of images for each category.

To generate the images, we utilized seven state-of-the-art text-to-image models based on the Diffusion model principle: [Stable Diffusion 1.5](https://huggingface.co/runwayml/stable-diffusion-v1-5), [Stable Diffusion 2](https://huggingface.co/stabilityai/stable-diffusion-2), [Stable Diffusion-XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0), [Stable Diffusion-XL Turbo](https://huggingface.co/stabilityai/sdxl-turbo), [DALL·E 3](https://www.bing.com/images/create), [Adobe Firefly](https://firefly.adobe.com), and [Midjourney](https://www.midjourney.com).

Each image was generated using a standardized text prompt format: `'Front face of <a/an> <Ethnicity> <Gender> in <his/her> <early/mid/late> <age> in color at 4K resolution'`. For example: `'Front face of a European woman in her early 20s in color at 4K resolution'`. 
We generated a minimum of 40 images for each 'early', 'mid', and 'late' category, resulting in at least 120 images per age group. Across four age groups, this totals at least 480 images per gender, and with two genders, we have a minimum of 960 images per ethnicity. With six ethnicities, the dataset contains a minimum of 5,760 images per generative tool. We manually curated the dataset to select the highest-quality images, discarding those with defective facial features.
### Dataset Details

| Model                      | Interface Used                | Images Generated | Ethnicities Covered                                  | Gender, Age Range                       |
|----------------------------|-------------------------------|------------------|------------------------------------------------------|-----------------------------------------|
| Stable Diffusion 1.0       | Hugging Face                  | 5,760            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| Stable Diffusion 2.0       | Hugging Face                  | 5,778            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| Stable Diffusion XL        | Hugging Face, Clip Drop        | 6,211            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| Stable Diffusion XL-Turbo  | Hugging Face                  | 5,800            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| DALL·E 3                   | Bing                          | 5,766            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| Adobe Firefly              | Adobe Official                | 5,954            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |
| Midjourney                 | Discord Bot                   | 5,858            | African, American, East Asian, European, Indian, South Asian | 20 to 60 years of age, both male and female |






## Access


If you would like to download the DiffSynFace dataset, please fill out [this](https://docs.google.com/forms/d/1GIFmg3hzOK5jbz3S6CnNzhS-1iYyar3zsnpigy35qNI/edit) google form and, once accepted, we will send you the link to the dataset.
Students should request access to DiffSynFace through their academic advisor/ supervisor.

## Help

If you have any questions, please contact us at rnlab60@myyahoo.com

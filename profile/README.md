# Who we are 🙋‍ 
[SmartForest](https://smartforest.no/) is a centre for research-based innovation (SFI) 🚀 funded by the Norwegian Reseacrh Council (NFR SFI project no. 309671) and aimed at bringing the industry 4.0 to the Norwegian forest sector. The centre is jointly coordinated by NIBIO and NMBU, other partners include UiO and most of the forest industry actors in Norway.

# Purpose of this collection of repositories 
The purpose of this page is to release the methods 🛠️ developed within SmartForest for public use.

# Available repositories 👩‍🔬🧑‍🔬
The table below shows the repositories developed within SmartForest, and respective contributors and references to the scientific papers. The repos are in an increasing temporal order so as a general rule the latest ones 

## Single tree segmentation from point clouds 🌲✴︎
These include methods for forest 3D scene panoptic segmentation into single trees and various semantic classes. 
As a general rule, the latest one should be the best. However, ForAINet and SegmentAnyTree are very similar in terms of architecture, and the former includes more semantic layers (ground, low veg., stems, branches, leaves), so one might prefer ForAINet if one has TLS, MLS, or very high-resolution ULS data.

| Contributors  | Repository | Language | citation |
| ------------- | ------------- | ------------- |------------- |
| [Maciej Wielgosz](https://github.com/maciekwielgosz) | [Point2Tree](https://github.com/SmartForest-no/Point2tree) | Python | [Wielgosz et al. 2023](https://www.mdpi.com/2072-4292/15/15/3737)|
|[Binbin Xiang](https://github.com/bxiang233) | [ForAINet](https://github.com/bxiang233/ForAINet) |Python | [Xiang et al. 2024](https://www.sciencedirect.com/science/article/pii/S0034425724000890) |
|[Maciej Wielgosz](https://github.com/maciekwielgosz) | [SegmentAnyTree](https://github.com/SmartForest-no/SegmentAnyTree) |Python | [Wielgosz et al. 2024](https://www.sciencedirect.com/science/article/pii/S0034425724003936)|

## UAV RGB models
| Contributors  | Repository | Language | citation |
| ------------- | ------------- | ------------- |------------- |
| [Stefano Puliti](https://github.com/stefp)  and [Saheba Bhatnagar](https://github.com/sabh92)| [wheelRuts_semanticSegmentation](https://github.com/SmartForest-no/wheelRuts_semanticSegmentation)  | Python | [Bhatnagar et al. 2022](https://academic.oup.com/forestry/article/95/5/698/6627280)|
|[Stefano Puliti](https://github.com/stefp) | [SmartForest_UAV_damage_detection](https://github.com/stefp/SmartForest_UAV_damage_detection) |Python | [Puliti and Astrup 2022](https://www.sciencedirect.com/science/article/pii/S1569843222001431)|

# RGB road segmentation
| Contributors  | Repository | Language | citation |
| ------------- | ------------- | ------------- |------------- |
| [Mostafa Hoseini](https://github.com/orgs/SmartForest-no/people/mostafa-nibio)  | [RoadSens](https://github.com/mostafa-nibio/roadsens_feature_extraction_models)  | Python | [Hoseini et al. 2024](https://www.sciencedirect.com/science/article/pii/S0168169924011013)|

https://github.com/mostafa-nibio/roadsens_feature_extraction_models
## Wood quality
These include various deep learning methods for extraction of wood quality parameters

| Contributors  | Repository | Language | citation |
| ------------- | ------------- | ------------- |------------- |
| [Stefano Puliti](https://github.com/stefp)  and [Nicolas Cattaneo]| [whorl_detector](https://github.com/SmartForest-no/YOLOv5-whorlDetector)  | R | [Puliti et al. 2023](https://academic.oup.com/forestry/article-abstract/96/1/37/6628789)|
|[Stefano Puliti](https://github.com/stefp) | [BranchPoseNet](https://github.com/stefp/BranchPoseNet) |Python | [Puliti et al. 2024](https://arxiv.org/abs/2409.14755)|

## Allometric functions 
These include allometric functions to estimate stem taper and functions to optimize bucking.

| Contributors  | Repository | Language | citation |
| ------------- | ------------- | ------------- |------------- |
| [Johannes Rahlf](https://github.com/JohannesRahlf) and [Endre Hansen](https://github.com/endrh) | [taperNOR](https://github.com/SmartForest-no/taperNOR)  | R | [Hansen et al. 2023](https://www.tandfonline.com/doi/full/10.1080/02827581.2023.2243821) |
|[Lennart Noordemeer](https://github.com/lennartnoordermeer) | [OptBuck](https://github.com/SmartForest-no/optBuck) |R | Unpublished |

# Contribute 🚧🔨
Keep in mind that the repos above are mostly experimental code, meaning that there might be still bugs. If you happen to find one, make us happy by filling an issue with all the details to reproduce it the best you can.


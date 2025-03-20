# Fruit Datasets Analysis from Open Source Repositories

This document provides an analysis of fruit-related datasets available on [PapersWithCode](https://paperswithcode.com/datasets?q=fruit&v=lst&o=match) and other major repositories. 

## Overview

There are numerous datasets focused on fruits for various computer vision and machine learning tasks. These datasets support research in areas like fruit detection, quality assessment, disease identification, classification, and other specialized applications.

## Dataset Summary (Partial List)

| # | Dataset Name | Fruit Type | Primary Task | Size |
|---|--------------|------------|--------------|------|
| **Single Fruit Datasets** |
| 1 | AppleBBCH81 | Apple | Ripeness Classification, Object Detection | 3008×2000 → 640×640 crops (30% overlap) |
| 2 | AppleScabFDs | Apple (with scab) | Disease Detection, Classification | Multiple smartphone resolutions (12-48MP) |
| 3 | AppleScabLDs | Apple leaves | Disease Detection, Classification | Field images from multiple devices |
| 4 | Embrapa ADD 256 | Apples | Object Detection, Aerial Monitoring | 1,139 drone images (2,471 apples) |
| 5 | CherryBBCH72 | Cherry fruitlets | Development Tracking, Object Detection | 3008×2000 → 640×640 crops |
| 6 | CherryBBCH81 | Cherry | Ripeness Classification, Object Detection | 6016×4000 → 640×640 crops |
| 7 | Lemons quality control | Lemon | Quality Control, Segmentation | 2,690 annotated images (1056×1056) |
| 8 | Pear640 | Pear | Object Detection | YOLO-optimized 640×640 crops |
| 9 | DiaMOS Plant | Pear fruit and leaves | Disease Diagnosis, Classification | 3,505 field images (13.1 GB) |
| 10 | Pistachio Image Dataset | Pistachio | Variety Classification | 2,148 images (16 attributes each) |
| 11 | TomatoPlantfactoryDataset | Tomato | Object Detection | Plant factory environment images |
| 12 | MinneApple | Apple | Detection and Segmentation | 1,000 images (41k+ instances) |
| 13 | AppleBBCH76 | Apple | Development Tracking | BBCH76 stage documentation |
| 14 | UFO Cherry Tree Point Clouds | Cherry | Tree Structure Analysis | 82 3D point clouds |
| **Multiple Fruit Datasets** |
| 15 | AIM-500 | Various (10 fruit images) | Image Matting | 500 high-quality matting pairs |
| 18 | Herbarium 2021 Half-Earth | Various (includes fruit data) | Classification | Botanical specimen images |
| 22 | Synthetic Plant Dataset | Plants and fruits | Object Detection | 10 growth sequences (0-19 days) |
| 24 | WINGBEATS | Insect detection (fruit flies) | Audio Classification | Flight sound recordings |
| 27 | ACFR Orchard Fruit Dataset | Apples, Mangoes, Almonds | Object Detection, Segmentation | 3,704 orchard images |
| 28 | fruit-SALAD | 10 fruit categories | Style and Semantic Similarity | 10,000 synthetic images (15.8 GB) |
| 29 | Multi-species Fruit Flower Detection | Apple, Peach, Pear | Flower Segmentation | 197 images (1.74 GB) |
| 30 | DeepHS Fruit v2 | Avocados, Kiwis, Persimmons, Papayas, Mango | Hyperspectral Ripeness Prediction | 5,689 hyperspectral recordings |
| 31 | RawRipe Dataset | 10 fruit types | Maturity Recognition | Raw/ripe pairs across 10 species |
| 32 | VegFru | 292 vegetable and fruit classes | Fine-Grained Visual Categorization | 160,000+ categorized images |
| 33 | Fruits Dataset for Classification | Strawberries, Peaches, Pomegranates | Fresh vs. Rotten Classification | 1,500 controlled images (300×300) |
| 34 | Fruits 360 | 131 classes of fruits/vegetables | Classification | 90,483 images (100×100 white bg) |

## Detailed Analysis

### TomatoPlantfactoryDataset (Tomato Detection)
- **Source**: Published on PapersWithCode and Elsevier
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/tomato-detection)
- **Content**: Dataset of tomato fruits images for object detection in complex plant factory environments
- **Features**:
  - Micro tomato variety captured under different artificial lighting conditions
  - Includes variations in tomato fruit, complex lighting environment changes, distance changes
  - Also captures occlusion and blurring scenarios
  - Designed specifically for plant factory environments
- **Applications**:
  - Intelligent control systems for plant factories
  - Operation robots and harvesting automation
  - Fruit maturity assessment
  - Yield estimation
  - Rapid classification and statistics
- **Significance**:
  - Addresses the gap in datasets for tomato harvesting automation in plant factories
  - Facilitates development of control systems and harvesting robots
  - Enables research on automation in controlled agriculture environments
- **License**: CC BY 4.0 DEED

### CherryBBCH72 (Cherry fruitlets BBCH72)
- **Source**: Presented in the article "Autonomous Yield Estimation System for Small Commercial Orchards Using UAV and AI" by Kodors et al.
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/cherrybbch72) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/cherrybbch72)
- **Content**: Photos of cherry fruitlets at BBCH development stage 72
  - BBCH-scale: 7 - development of fruit; 72 - fruit size up to 20mm
- **Features**:
  - Two photo images for each tree – perpendicular tree-facing view and oblique view
  - Images annotated using makesense.ai tool
  - Original 3008×2000 images automatically cropped to 640×640 with 30% overlap
  - Manual validation of cropped images
  - Saved in YOLO format for object detection tasks
- **Location**: LatHort orchard in Dobele
- **Applications**:
  - Object detection of early-stage fruits
  - Growth monitoring and phenology tracking
  - Yield estimation for small commercial orchards
  - UAV-based agricultural monitoring
- **Paper**: Kodors, S.; Zarembo, I.; Lācis, G.; Litavniece, L.; Apeināns, I.; Sondors, M.; Pacejs, A. "Autonomous Yield Estimation System for Small Commercial Orchards Using UAV and AI." Drones 2024, 8, 734.
- **License**: CC BY 4.0

### AppleBBCH81 (Apple Fruits BBCH 81-85)
- **Source**: Presented in the article "Autonomous Yield Estimation System for Small Commercial Orchards Using UAV and AI" by Kodors et al.
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/applebbch81) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/applebbch81)
- **Content**: Photos of apple fruits at maturity of fruit and seed (BBCH stage 81-85)
  - BBCH-scale: 8 - maturity of fruit and seed; 81 - beginning of ripening; 85 - advanced ripening
- **Features**:
  - Two photo images for each tree – perpendicular tree-facing view and oblique view
  - Images annotated using makesense.ai tool
  - Original 3008×2000 images automatically cropped to 640×640 with 30% overlap
  - Manual validation of cropped images
  - Saved in YOLO format for object detection tasks
- **Location**: LatHort orchard in Dobele
- **Applications**:
  - Object detection of ripening fruits
  - Growth monitoring and phenology tracking
  - Ripeness assessment and classification
  - Yield estimation for small commercial orchards
  - UAV-based agricultural monitoring
- **Paper**: Kodors, S.; Zarembo, I.; Lācis, G.; Litavniece, L.; Apeināns, I.; Sondors, M.; Pacejs, A. "Autonomous Yield Estimation System for Small Commercial Orchards Using UAV and AI." Drones 2024, 8, 734.
- **License**: CC BY 4.0

### CherryBBCH81 (Cherry Fruits)
- **Source**: Presented in the article "Cherry Fruitlet Detection using YOLOv5 or YOLOv8?" by Apeināns et al.
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/cherrybbch81) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/cfruitlets81-640)
- **Content**: Photos of cherry fruits at the beginning of fruit coloration (BBCH stage 81)
  - BBCH-scale: 8 - ripening of berries; 81 - beginning of ripening: berries begin to develop variety-specific color
- **Features**:
  - Two photo images for each tree – perpendicular tree-facing view and oblique view
  - Images annotated using makesense.ai tool
  - Original 6016×4000 images automatically cropped to 640×640 with 30% overlap
  - Manual validation of cropped images
  - Saved in YOLO format for object detection tasks
- **Location**: LatHort orchard in Dobele
- **Applications**:
  - Object detection of ripening fruits
  - Growth monitoring and phenology tracking
  - Ripeness assessment and classification
  - Yield estimation for small commercial orchards
  - UAV-based agricultural monitoring
- **Paper**: Ilmārs Apeināns, Marks Sondors, Lienīte Litavniece, Sergejs Kodors, Imants Zarembo, Daina Feldmane. "Cherry Fruitlet Detection using YOLOv5 or YOLOv8?" In Proceedings of the 15th International Scientific and Practical Conference "Environment. Technology. Resources", Rezekne, Latvia, June 27-28, 2024, vol. 2, pp. 29-33. doi: 10.17770/etr2024vol2.8013
- **License**: CC BY 4.0

### Lemons quality control dataset
- **Source**: Introduced by Maciej Adamiak at SoftwareMill
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/lemons-quality-control-dataset) and [GitHub](https://github.com/softwaremill/lemon-dataset)
- **Content**: Dataset created to investigate fruit quality control
  - **Total Size**: 2690 annotated images (1056 × 1056 pixels)
  - **Format**: COCO format
- **Features**:
  - Detailed annotations of various quality issues and defects
  - Manually annotated using CVAT (Computer Vision Annotation Tool)
  - Each image has a specific identifier format (e.g., 0037_G_I_120_A)
  - Annotations include both boolean attributes and region-based segmentation
- **Annotation Categories**:
  - **Condition**: healthy (boolean), greening (boolean)
  - **Image Quality**: blurry, cropped, unnatural color, no data (all boolean)
  - **Defects**: illness (region), gangrene (region), mould (region), blemish (region + boolean), dark style remains (region), pedicel (region), artifact (region)
- **Applications**:
  - Fruit quality assessment and grading
  - Defect detection and classification
  - Computer vision for agricultural products
  - Automated inspection systems
  - Semantic and panoptic segmentation research
- **DOI**: 10.5281/zenodo.3965568
- **License**: MIT
- **Paper**: Adamiak, M. (2020, July). Lemons quality control dataset. SoftwareMill. https://doi.org/10.5281/zenodo.3965568

### AppleScabFDs (Apple Scab Fruits Dataset)
- **Source**: Introduced by Kodors et al. in "Apple Scab Detection using CNN and Transfer Learning"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/applescabfds) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/applescabfds)
- **Content**: Images of apples infected by apple scab disease
  - **Organization**: Grouped in two folders - "Healthy" and "Scab"
- **Collection Methodology**:
  - Collected from different locations in Latvia
  - Captured by the Institute of Horticulture (LatHort)
  - Part of project "lzp-2019/1-0094 Application of deep learning and datamining for the study of plant-pathogen interaction: the case of apple and pear scab"
  - Goal: Create mobile application for apple scab detection using CNNs
- **Image Acquisition**:
  - **Devices**: Smartphone cameras (12 MP, 13 MP, 48 MP) and digital compact camera (10 MP)
  - **Conditions**: Field conditions in orchards
  - **Times**: Morning (9:00-10:00), noon (12:00-14:00), evening (16:00-17:00)
  - **Lighting**: Both sunny days (hard light) and overcast days (soft light)
  - **Framing**: Objects centered, occupying most of the image area
  - **Background**: May include other leaves or fruits
  - **Views**: Same object photographed from multiple viewpoints
- **Applications**:
  - Apple disease identification
  - Mobile disease detection applications
  - Transfer learning for plant disease classification
  - Field diagnostics for orchard management
- **Paper**: S. Kodors, G. Lacis, O. Sokolova, V. Zhukovs, I. Apeinans and T. Bartulsons. 2021. "Apple Scab Detection using CNN and Transfer Learning." Agronomy Research, 19(2), 507–519. doi: 10.15159/AR.21.045
- **License**: CC BY-NC-ND 4.0
- **Tasks**: Image Classification, Transfer Learning

### Herbarium 2021 Half-Earth
- **Focus**: Plant specimens including fruit-bearing plants
- **Applications**: Ecosystem health monitoring, biodiversity research
- **Research Impact**: 2 papers and 1 benchmark

### DiaMOS Plant (A Dataset for Diagnosis and Monitoring Plant Disease)
- **Source**: Introduced by Fenu and Malloci from University of Cagliari
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/diamos-plant) and [Zenodo](https://zenodo.org/records/5557313)
- **Content**: Comprehensive dataset for diagnosis and monitoring plant disease
  - **Total Size**: 3,505 images of pear fruit and leaves (13.1 GB)
  - **Disease Coverage**: 4 leaf diseases with 4 levels of severity and 4 fruit stages
- **Features**:
  - Field-collected data (not laboratory)
  - Captures natural progression and severity of diseases
  - Designed for both classification and object detection tasks
  - Includes detailed documentation on dataset construction methods
- **Applications**:
  - Plant disease prediction and diagnosis
  - Severity level classification
  - Monitoring disease progression
  - Agricultural decision support systems
  - Precision agriculture
- **Paper**: Fenu, G.; Malloci, F.M. "DiaMOS Plant: A Dataset for Diagnosis and Monitoring Plant Disease." Agronomy 2021, 11, 2107.
- **DOI**: 10.3390/agronomy11112107
- **Additional resources**: GitHub code repository: [leaf-disease-toolbox](https://github.com/mallociFrancesca/leaf-disease-toolbox)
- **Similar Datasets**: PlantVillage
- **License**: CC BY 4.0
- **Language**: English

### SuperMat
- **Note**: Described as resulting from a "fruitful collaboration" between computer scientists and material scientists
- **Features**: Validated by domain experts
- **Research Impact**: 4 papers and 1 benchmark

### Embrapa ADD 256 (Embrapa Apples by Drones Detection Dataset)
- **Source**: Introduced by Santos & Gebler in "A methodology for detection and location of fruits in apples orchards from aerial images"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/embrapa-add-256) and [GitHub](https://github.com/thsant/add256)
- **Content**: Low-resolution aerial images for apple detection in orchards
  - **Total Size**: 1,139 images containing 2,471 annotated apples
  - **Image Format**: 8-bit RGB images (256×256 pixels)
  - **Data Splits**: 1,025 training images (2,204 apples), 114 test images (267 apples)
- **Annotation Format**:
  - Apples marked with circular markers (center coordinates and radius)
  - Annotations stored in JSON format
  - Example: `{"cx": 116, "cy": 117, "r": 10}`
  - Single-annotator dataset (noted as potentially "noisy")
- **Collection Methodology**:
  - Captured at Embrapa's Temperate Climate Fruit Growing Experimental Station (Vacaria-RS, Brazil)
  - Apple varieties: Fuji and Gala (equal proportions)
  - Acquisition date: December 13, 2018
  - Equipment: DJI Phantom 4 Pro drone at 12m height
  - Views: Mix of nadir and non-nadir views for extensive canopy coverage
  - Procedure: Random patches extracted from original drone imagery
- **Annotation Tool**: VGG Image Annotator (VIA)
- **Applications**:
  - Apple detection in low-resolution aerial imagery
  - UAV-based orchard monitoring
  - Yield estimation in fruit production
  - Precision agriculture research
  - Agricultural informatics
- **Data Loader**: Includes Jupyter Notebook for loading as PyTorch Dataset
- **Paper**: Santos, T. T., & Gebler, L. (2021). "A methodology for detection and location of fruits in apples orchards from aerial images." arXiv:2110.12331.
- **License**: Creative Commons BY-NC 4.0 (Attribution-NonCommercial 4.0 International)
- **DOI**: 10.5281/zenodo.5557313
- **Funding**: Supported by Embrapa SEG Project 01.14.09.001.05.04 "Image-based metrology for Precision Agriculture and Phenotyping" and FAPESP grant (2017/19282-7)

### ACFR Orchard Fruit Dataset
- **Source**: Australian Centre for Field Robotics, The University of Sydney
- **Website**: [data.acfr.usyd.edu.au/ag/treecrops/2016-multifruit/](https://data.acfr.usyd.edu.au/ag/treecrops/2016-multifruit/)
- **Content**:
  - **Apples**: 1,120 images (308×202, 8-bit/color RGB) with circle and pixel-wise annotations
  - **Mangoes**: 1,964 images (500×500, 16-bit/color RGB) with rectangle annotations
  - **Almonds**: 620 images (308×202, 8-bit/color RGB) with rectangle annotations
- **Collection**: Images collected from actual orchards in Australia using robotic platforms
- **Features**: Includes train/test/validation splits, pixel-level segmentation for apples
- **Performance**: Published F1-scores - Apple: 0.904, Mango: 0.908, Almond: 0.775
- **Research Impact**: Used in multiple studies on fruit detection, yield estimation, and image segmentation
- **Applications**: Automated fruit detection, yield estimation, robotic harvesting

### fruit-SALAD
- **Source**: Tallinn University, published on Zenodo
- **Website**: [zenodo.org/records/11158522](https://zenodo.org/records/11158522)
- **Content**: 10,000 synthetic images of fruit depictions
  - 10 fruit categories with 100 instances each
  - 10 distinguishable artistic styles with 100 instances each
- **Creation Method**: Generated using Stable Diffusion XL and StyleAligned with carefully crafted text prompts
- **Features**: 
  - Includes embeddings, grid overviews, labels, model heatmaps, and model vectors
  - Balanced representation across categories and styles
  - Available with complete prompt data
- **Size**: 15.8 GB of data including:
  - Main dataset (14.7 GB)
  - Embeddings (616.8 MB)
  - Grid overviews (473 MB)
- **Purpose**: Comparative analysis of similarity perception in different computational models
- **License**: Creative Commons Attribution 4.0 International (for academic research only)
- **DOI**: 10.5281/zenodo.11158522
- **Publication**: Published in Scientific Data, 12(1), 254, 2024
- **Code**: Reproduction code available on [GitHub](https://github.com/Style-Aligned-Artwork-Datasets/fruit-SALAD)

### Multi-species Fruit Flower Detection Dataset
- **Source**: USDA Agricultural Research Service (ARS)
- **Website**: [agdatacommons.nal.usda.gov](https://agdatacommons.nal.usda.gov/articles/dataset/Data_from_Multi-species_fruit_flower_detection_using_a_refined_semantic_segmentation_network/24852636)
- **Content**: Images of flowers from three different fruit species with ground truth segmentation masks
  - **Apple A**: 147 images acquired with Canon EOS 60D
  - **Apple B**: 15 images acquired with GoPro HERO 5
  - **Peach**: 20 images acquired with GoPro HERO 5
  - **Pear**: 15 images acquired with GoPro HERO 5
- **Features**:
  - Binary ground truth images (white for flower pixels, black for non-flower)
  - Includes predefined training/validation splits
  - Images captured under a range of natural conditions
- **Size**: 1.74 GB
- **Purpose**: Flower detection for orchard crop management and fruit load estimation
- **Applications**:
  - Flower identification in uncontrolled environments
  - Yield prediction
  - Orchard management
- **License**: U.S. Public Domain
- **Authors**: Philipe A. Dias, Amy Tabb, Henry Medeiros
- **Funding**: ARS Integrated Orchard Management and Automation for Deciduous Tree Fruit Crops

### DeepHS Fruit v2
- **Source**: Introduced by Varga et al. in "Measuring the Ripeness of Fruit with Hyperspectral Imaging and Deep Learning"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/deephs-fruit-v2)
- **Content**: Hyperspectral recordings of ripening fruits with destructive measurement labels
  - **Total Size**: 5,689 recordings (1,018 labeled + 4,671 unlabeled)
  - **Fruit Types**: Avocados, Kiwis, Persimmons, Papayas, Mangos
- **Features**:
  - Three measurement categories: firmness, sweetness, and overall ripeness
  - Four measurement series performed
  - Captured using three different hyperspectral cameras:
    - Specim FX 10
    - INNO-SPEC Redeye 1.7
    - Corning microHSI 410 Vis-NIR Hyperspectral Sensor
- **Applications**:
  - Non-destructive fruit ripeness assessment
  - Sugar content prediction
  - Firmness estimation
- **Best Model**: Fruit-HSNet (as benchmarked on PapersWithCode)
- **Tasks**: 
  - Classification
  - Hyperspectral Image-Based Fruit Ripeness Prediction

### RawRipe Dataset
- **Source**: Introduced by Rao Jerripothula et al. in "Fruit Maturity Recognition from Agricultural, Market and Automation Perspectives"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/rawripe-dataset)
- **Content**: Images of 10 types of fruits in both raw and ripe states
  - **Fruit Types**: Apple, banana, coconut, guava, litchi, mango, orange, papaya, pomegranate, and strawberry
- **Features**:
  - Supports three different classification tasks:
    1. Raw vs. ripe for a specific fruit (agricultural perspective)
    2. Raw vs. ripe for any fruit (market perspective) 
    3. Multi-class/label classification: fruit-type + maturity state (automation perspective)
- **Applications**:
  - Fruit quality assessment in agricultural settings
  - Market-level ripeness classification
  - Automated sorting systems
- **Best Model**: VGG16 + Logistic Regression (as benchmarked on PapersWithCode)
- **Publication**: IECON 2021 – 47th Annual Conference of the IEEE Industrial Electronics Society
- **Paper Link**: [IEEE Xplore](https://ieeexplore.ieee.org/document/9589215)

### VegFru
- **Source**: Introduced by Hou et al. in "VegFru: A Domain-Specific Dataset for Fine-Grained Visual Categorization"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/vegfru)
- **Content**: Domain-specific dataset for fine-grained visual categorization of vegetables and fruits
  - **Total Size**: 160,000+ images
  - **Structure**: 25 upper-level categories and 292 subordinate classes
  - **Coverage**: At least 200 images per subordinate class
- **Features**:
  - Hierarchical labeling system
  - Categorizes vegetables and fruits by eating characteristics
  - Each image contains at least one edible part with the same cooking usage
- **Applications**:
  - Fine-grained visual categorization
  - Image retrieval
  - Color constancy
  - Culinary applications
- **Data Loader**: Available (ustc-vim/vegfru)
- **Paper Link**: [ICCV 2017](https://openaccess.thecvf.com/content_ICCV_2017/papers/Hou_VegFru_A_Domain-Specific_ICCV_2017_paper.pdf)

### Fruits Dataset for Classification
- **Source**: Introduced by Femling et al. in "Fruit and Vegetable Identification Using Machine Learning for Retail Applications"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/fruits-dataset-for-classification)
- **Content**: Controlled images of fruits in fresh and rotten states
  - **Total Size**: 1,500 images
  - **Fruit Types**: Strawberries, peaches, pomegranates
  - **Distribution**: 250 fresh and 250 rotten images for each fruit type
- **Features**:
  - Consistent format: white background, JPG format, 300×300 pixel size
  - Controlled lighting conditions
  - Balanced classes between fresh and rotten states
- **Applications**:
  - Agricultural sorting and grading systems
  - Retail automated checkout systems
  - Food industry quality control
  - Educational purposes for teaching machine learning concepts
- **License**: Apache 2.0
- **Similar Datasets**: Fruits 360

### MinneApple
- **Source**: Introduced by Häni et al. in "MinneApple: A Benchmark Dataset for Apple Detection and Segmentation"
- **Website**: [GitHub](https://github.com/nicolaihaeni/MinneApple)
- **Content**: Benchmark dataset specifically for apple detection and segmentation
  - **Total Size**: 1,000 images containing over 41,000 annotated object instances
- **Features**:
  - Precise polygonal masks for each apple instance
  - Support for object detection, localization, and segmentation tasks
  - Includes data for patch-based counting of clustered fruits
  - Designed for real-world orchard environments
- **Applications**:
  - Precision agriculture
  - Automated fruit counting
  - Yield estimation
  - Robotic harvesting systems
  - Orchard management
- **Data Loader**: Available (nicolaihaeni/MinneApple) with 117 stars
- **Similar Datasets**: WGISD (Wine Grape Instance Segmentation Dataset)

### AppleBBCH76
- **Source**: Available on Kaggle
- **Website**: [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/applebbch76)
- **Content**: Images of apples at the BBCH76 growth stage
  - BBCH76 corresponds to the stage where fruit has reached about 60% of its final size
- **Features**:
  - Documents a specific phenological growth stage in apple development
  - Part of the BBCH series of fruit datasets (along with AppleBBCH81 and CherryBBCH72/81)
- **Applications**:
  - Growth monitoring and phenology tracking
  - Precision agriculture
  - Yield estimation
  - Plant development research
- **Context**: The BBCH scale is a system for uniform coding of phenologically similar growth stages of plants, with BBCH76 representing a specific developmental milestone for apples

### UFO Cherry Tree Point Clouds
- **Source**: Introduced in "Semantics-guided Skeletonization of Sweet Cherry Trees for Robotic Pruning"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/ufo-cherry-tree-point-clouds) and [Google Drive](https://drive.google.com/drive/folders/1V2XNrYTp715YA0iOg8Ewn-oLq1Bha6m_)
- **Content**: Collection of 3D point cloud data for cherry trees
  - **Total Size**: 82 scanned Upright Fruiting Offshoot (UFO) cherry tree point clouds
- **Features**:
  - 3D spatial representation of cherry tree structure
  - Specifically focused on UFO training system (planar architecture for mechanized operations)
  - Designed for tree structure analysis and automated pruning applications
- **Applications**:
  - Robotic pruning of fruit trees
  - Automated tree structure analysis
  - Phenotyping of tree architecture
  - Precision horticulture
  - Autonomous orchard management
- **Significance**: 
  - One of few 3D point cloud datasets for fruit trees
  - Enables research on automation of pruning, a labor-intensive task
  - Supports development of robotic systems for orchard management

### Fruits 360
- **Source**: Introduced by Muresan and Oltean in "Fruit recognition from images using deep learning"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/fruits-360-1) and [GitHub](https://github.com/Horea94/Fruit-Images-Dataset)
- **Content**: Comprehensive collection of fruit and vegetable images
  - **Total Size**: 90,483 images
  - **Split**: 67,692 training images, 22,688 test images
  - **Classes**: 131 different fruits and vegetables
- **Features**:
  - Consistent format: 100×100 pixel images
  - Controlled acquisition: fruits placed on white background
  - Captured on rotating platform (3 rpm) with Logitech C920 camera
  - Background separation using flood fill algorithm
  - Includes multiple varieties of the same fruit type as different classes
  - Filename format indicates rotation state (e.g., r_image_index_100.jpg)
- **Fruit Varieties**: Includes diverse range of common and exotic fruits
  - Multiple apple varieties (Crimson Snow, Golden, Red Delicious, etc.)
  - Various berries (Blueberry, Raspberry, Strawberry, etc.)
  - Tropical fruits (Banana, Mango, Pineapple, etc.)
  - Citrus fruits (Orange, Lemon, Grapefruit, etc.)
  - And many others
- **Applications**:
  - Automated fruit identification and sorting
  - Machine learning education and benchmarking
  - Retail and inventory systems
- **License**: MIT License
- **Similar Datasets**: Fruits Dataset for Classification, ETHEC, Plant Seedlings Dataset

### Pear640
- **Source**: Presented in the paper "RAPID PROTOTYPING OF PEAR DETECTION NEURAL NETWORK WITH YOLO ARCHITECTURE IN PHOTOGRAPHS" by Kodors et al.
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/pear640) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/pear640)
- **Content**: Annotated photographs of pear orchard for object detection tasks
  - Contains only one class: "Pear fruits"
  - Optimized for use with YOLO architecture
- **Features**:
  - Images annotated for object detection
  - Consistent with other fruit datasets from the same research group
  - Designed for rapid prototyping of detection models
- **Applications**:
  - Pear detection in orchard environments
  - Yield estimation
  - Automated fruit counting
  - Development of agricultural computer vision systems
- **Paper**: Sergejs Kodors, Marks Sondors, Gunārs Lācis, Edgars Rubauskis, Ilmārs Apeināns, Imants Zarembo. "RAPID PROTOTYPING OF PEAR DETECTION NEURAL NETWORK WITH YOLO ARCHITECTURE IN PHOTOGRAPHS," In Proceedings of the International Scientific and Practical Conference "Environment. Technology. Resources.", Rezekne, Latvia, June 15-16, 2023, vol. 1, pp. 81-85. doi: 10.17770/etr2023vol1.7293
- **License**: CC BY 4.0
- **Tasks**: 2D Object Detection

### AppleScabLDs (Apple Scab Leaves Dataset)
- **Source**: Introduced by Kodors et al. in "Apple Scab Detection using CNN and Transfer Learning"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/applescablds) and [Kaggle](https://www.kaggle.com/datasets/projectlzp201910094/applescablds)
- **Content**: Images of apple leaves infected by apple scab disease
  - **Organization**: Grouped in two folders - "Healthy" and "Scab"
- **Collection Methodology**:
  - Collected from different locations in Latvia
  - Captured by the Institute of Horticulture (LatHort)
  - Part of project "lzp-2019/1-0094 Application of deep learning and datamining for the study of plant-pathogen interaction: the case of apple and pear scab"
  - Goal: Create mobile application for apple scab detection using CNNs
  - **Image Acquisition**:
    - **Devices**: Smartphone cameras (12 MP, 13 MP, 48 MP) and digital compact camera (10 MP)
    - **Conditions**: Field conditions in orchards
    - **Times**: Morning (9:00-10:00), noon (12:00-14:00), evening (16:00-17:00)
    - **Lighting**: Both sunny days (hard light) and overcast days (soft light)
    - **Framing**: Leaves centered and occupying most of the image area
    - **Background**: May include other leaves or fruits
    - **Views**: Same leaf photographed from multiple viewpoints
- **Applications**:
  - Early disease detection in apple orchards
  - Mobile disease diagnosis applications
  - Transfer learning for plant disease classification
  - Field diagnostics for orchard management
  - Preventive disease control measures
- **Paper**: S. Kodors, G. Lacis, O. Sokolova, V. Zhukovs, I. Apeinans and T. Bartulsons. 2021. "Apple Scab Detection using CNN and Transfer Learning." Agronomy Research, 19(2), 507–519. doi: 10.15159/AR.21.045
- **License**: CC BY-NC-ND 4.0
- **Tasks**: Image Classification, Transfer Learning
- **Language**: English

### Synthetic Plant Dataset
- **Source**: Introduced by Liu et al. in "Synthetic Dataset Generation for Adversarial Machine Learning Research"
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/synthetic-plant-dataset) and [GTS.ai](https://gts.ai/dataset-download/synthetic-plant-dataset/)
- **Content**: 3D point cloud data of fabricated plants for computer vision applications
  - **Structure**: 10 sequences, with each sequence containing 0-19 days of data at every growth stage
- **Features**:
  - Carefully curated collection of computer-generated images of plants
  - Mimics diverse appearance and growth stages of real plants
  - Provides controlled environment for machine learning model training
  - Enables consistent performance evaluation across environmental conditions
- **Applications**:
  - Plant phenotyping at scale (analyzing traits, genetic characteristics)
  - Crop monitoring for precision agriculture
  - Object detection for identifying plants, fruits, and diseases
  - Training and benchmarking computer vision algorithms
  - Bridging gap between synthetic and real data
- **Significance**:
  - Addresses limitations in real-world data collection
  - Enables more efficient code development
  - Facilitates agricultural monitoring and disease diagnosis research
  - Supports development of remote sensing techniques
- **Tasks**: Synthetic Data Generation, Object Detection
- **Similar Datasets**: APRICOT
- **Language**: English

### Pistachio Image Dataset
- **Source**: Introduced by Ozkan et al. in "Classification of Pistachio Species Using Improved K-NN Classifier" and further used by Singh et al.
- **Website**: [PapersWithCode](https://paperswithcode.com/dataset/pistachio-image-dataset) and [MuratKoklu.com](https://www.muratkoklu.com/datasets/)
- **Content**: High-resolution images of two pistachio varieties for classification
  - **Total Size**: 2,148 sample images
  - **Varieties**: Kirmizi (1,232 images) and Siirt (916 images) - major types grown in Turkey
- **Features**:
  - Images taken with high-resolution camera through computer vision system
  - Processed using image segmentation and feature extraction
  - Dataset includes 16 extracted attributes for each image
  - Designed for classification of economically important pistachio varieties
- **Applications**:
  - Automated separation and classification of pistachio varieties
  - Post-harvest industrial processes
  - Market differentiation (varieties have different prices, tastes, and nutritional values)
  - Variety identification for trade purposes
- **Classification Performance**:
  - Improved k-NN model: 94.18% accuracy
  - AlexNet: 94.42% accuracy
  - VGG16: 98.84% accuracy (best performing)
  - VGG19: 98.14% accuracy
- **Papers**:
  1. Ozkan, I.A., Koklu, M. and Saracoglu, R. (2021). "Classification of Pistachio Species Using Improved K-NN Classifier." Progress in Nutrition, 23(2). DOI: 10.23751/pn.v23i2.9686
  2. Singh, D., Taspinar, Y.S., Kursun, R., Cinar, I., Koklu, M., Ozkan, I.A., Lee, H-N. (2022). "Classification and Analysis of Pistachio Species with Pre-Trained Deep Learning Models." Electronics, 11(7), 981. DOI: 10.3390/electronics11070981
- **Train/Test Split**: 80% training, 20% test
- **Evaluation Metrics**: Sensitivity, specificity, precision, F-1 score, ROC curves, AUC values
- **License**: Public
- **Language**: English

## Application Categories

### Agricultural Applications
- **Growth Monitoring**: CherryBBCH72, AppleBBCH81, CherryBBCH81, AppleBBCH76
- **Disease Detection**: AppleScabFDs, AppleScabLDs, DiaMOS Plant
- **Disease Monitoring**: DiaMOS Plant
- **Yield Estimation**: Embrapa ADD 256, AK_FRAEX, ACFR Orchard Fruit Dataset, Multi-species Fruit Flower Detection, MinneApple, TomatoPlantfactoryDataset, CherryBBCH72, Pear640
- **Pest Management**: WINGBEATS (fruit flies)
- **Robotic Harvesting**: ACFR Orchard Fruit Dataset, MinneApple, TomatoPlantfactoryDataset
- **Flower Detection**: Multi-species Fruit Flower Detection
- **Ripeness Assessment**: AppleBBCH81, DeepHS Fruit v2, RawRipe Dataset
- **Quality Grading**: Fruits Dataset for Classification, Pistachio Image Dataset
- **Fruit Counting**: MinneApple, TomatoPlantfactoryDataset, Pear640, Embrapa ADD 256
- **Variety Identification**: Fruits 360, Pistachio Image Dataset
- **Developmental Stages**: AppleBBCH76, AppleBBCH81, CherryBBCH72, CherryBBCH81
- **Controlled Environment Agriculture**: TomatoPlantfactoryDataset
- **Tree Structure Analysis**: UFO Cherry Tree Point Clouds
- **Automated Pruning**: UFO Cherry Tree Point Clouds
- **Early Disease Warning Systems**: AppleScabLDs
- **Plant Phenotyping**: Synthetic Plant Dataset
- **Crop Monitoring**: Synthetic Plant Dataset
- **Aerial Orchard Monitoring**: Embrapa ADD 256

### Computer Vision Tasks
- **Object Detection**: TomatoPlantfactoryDataset, RPC, Synthetic Plant Dataset, ACFR Orchard Fruit Dataset, MinneApple, CherryBBCH72, AppleBBCH81, CherryBBCH81, Pear640, DiaMOS Plant, Embrapa ADD 256
- **Classification**: Grocery Store, Pistachio Image Dataset, RawRipe Dataset, VegFru, Fruits Dataset for Classification, Fruits 360, AppleScabFDs, DiaMOS Plant, AppleScabLDs
- **Fresh/Rotten Classification**: Fruits Dataset for Classification
- **Fine-Grained Categorization**: VegFru, Fruits 360
- **Image Matting**: AIM-500
- **Segmentation**: MatSeg, ACFR Orchard Fruit Dataset (apples), Multi-species Fruit Flower Detection, MinneApple
- **Instance Segmentation**: MinneApple
- **Visual Search**: VNBench
- **Image Retrieval**: VegFru
- **Image Generation**: DrawBench, fruit-SALAD
- **Style Analysis**: fruit-SALAD
- **Similarity Perception**: fruit-SALAD
- **Hyperspectral Analysis**: DeepHS Fruit v2
- **Multi-perspective Classification**: RawRipe Dataset
- **Color Constancy**: VegFru
- **Complex Lighting Conditions**: TomatoPlantfactoryDataset
- **Point Cloud Analysis**: UFO Cherry Tree Point Clouds
- **3D Structure Skeletonization**: UFO Cherry Tree Point Clouds
- **Transfer Learning**: AppleScabFDs, AppleScabLDs
- **Synthetic Data Generation**: Synthetic Plant Dataset, fruit-SALAD
- **Plant Growth Modeling**: Synthetic Plant Dataset
- **Variety Classification**: Pistachio Image Dataset, Fruits 360

### Dataset Size Categories
- **Very Large** (50,000+ images):
  - Fruits 360 (90,483 images)
  - VegFru (160,000+ images)
- **Large** (5,000-50,000 images):
  - Grocery Store (5,125 images)
  - fruit-SALAD (10,000 images)
- **Medium** (1,000-5,000 images):
  - ACFR Orchard Fruit Dataset (3,704 images)
  - Lemons quality control (2,690 images)
  - DiaMOS Plant (3,505 images)
  - MinneApple (1,000 images with 41,000+ instances)
  - Pistachio Image Dataset (2,148 images)
- **Small** (<1,000 images):
  - Multi-species Fruit Flower Detection (197 images)

### Domain Applications
- **Agricultural Production**: Multiple datasets
- **Food Industry**: RawRipe Dataset, VegFru, Fruits Dataset for Classification, Pistachio Image Dataset
- **Retail**: RPC, Grocery Store, Fruits Dataset for Classification, Pistachio Image Dataset
- **Culinary**: VegFru (organized by cooking usage)
- **Education**: Fruits Dataset for Classification, ScienceQA

### Quality Assessment
- **Ripeness Classification**: AppleBBCH81, DeepHS Fruit v2, RawRipe Dataset
- **Defect Detection**: Lemons quality control, AppleScabFDs
- **Freshness Evaluation**: Fruits Dataset for Classification
- **Material State Analysis**: MatSeg
- **Internal Property Prediction**: DeepHS Fruit v2 (sugar content, firmness)
- **Market-level Assessment**: RawRipe Dataset

### Research Applications
- **Benchmark Datasets**: AIM-500, Herbarium 2021, SuperMat, ScienceQA, fruit-SALAD, DeepHS Fruit v2, RawRipe Dataset
- **Educational Tools**: ScienceQA
- **Model Evaluation**: fruit-SALAD
- **Synthetic-to-Real Transfer**: Synthetic Plant Dataset

### Application Perspectives
- **Agricultural**: RawRipe Dataset (species-specific ripeness)
- **Market/Retail**: RawRipe Dataset (generic ripeness)
- **Automation**: RawRipe Dataset (multi-label classification)

### Data Modalities
- **RGB Images**: Most datasets including ACFR Orchard Fruit Dataset, fruit-SALAD
- **Hyperspectral Images**: DeepHS Fruit v2
- **Audio**: WINGBEATS
- **Generated/Synthetic**: fruit-SALAD, DrawBench
- **3D Point Clouds**: UFO Cherry Tree Point Clouds

### Dataset Source Type
- **Natural Images**: ACFR Orchard Fruit Dataset, Grocery Store, Lemons quality control, Multi-species Fruit Flower Detection
- **Synthetic/Generated**: fruit-SALAD, DrawBench, Synthetic Plant Dataset
- **Mixed/Augmented**: Synthetic Plant Dataset
- **Specialized Sensing**: DeepHS Fruit v2 (hyperspectral), UFO Cherry Tree Point Clouds (3D scans)

### Dataset Popularity
1. **High Impact** (50+ papers):
   - ScienceQA (277 papers)
   - DrawBench (67 papers)

2. **Medium Impact** (10-49 papers):
   - AIM-500 (23 papers)
   - RPC (17 papers)

3. **Low Impact** (1-9 papers):
   - Grocery Store (7 papers)
   - SuperMat (4 papers)
   - DiaMOS Plant (4 papers)

4. **No Documented Impact** (0 papers):
   - Multiple datasets including Micro Tomato, CherryBBCH72, Lemons quality control, etc.

## Research Opportunities

### 1. **Underutilized Datasets**
Many of the datasets with zero papers indicate potential for novel research. These underutilized datasets present opportunities for:
- **Cross-domain applications**, such as applying computer vision methods from retail to agriculture and vice versa.
- **Transfer learning** from more popular datasets (like Fruits 360) to those with fewer resources, expanding the scope of research.

### 2. **Cross-Domain Applications**
The intersection of different domains, like retail and agriculture, presents a rich area for innovation. For example:
- **Retail data** (e.g., **Fruits Dataset for Classification**) can help in developing **automated food quality control systems**.
- **Agricultural datasets** (e.g., **MinneApple**) can enhance **food quality monitoring** in the supply chain.

### 3. **Dataset Enhancement**
There are opportunities to enrich current datasets:
- **Combine datasets** for multi-stage fruit analysis, from growth monitoring to retail applications.
- **Augment datasets with synthetic data** to bridge gaps in underrepresented fruit species or growth stages.

### 4. **Multi-Modal Datasets**
Integrating visual data with other sensor modalities (like audio from **WINGBEATS** or hyperspectral data from **DeepHS Fruit v2**) will open avenues for more robust and accurate systems in agriculture.

### 5. **Synthetic-to-Real Transfer**
Datasets like **Synthetic Plant Dataset** and **fruit-SALAD** offer controlled environments for training models that can be transferred to real-world settings, helping with scalability and deployment in practical applications.

### 6. **Emerging Areas**
- **Robotic Pruning**: **UFO Cherry Tree Point Clouds** offers data for 3D point cloud analysis, enabling automation of pruning tasks.
- **Early Disease Detection**: **AppleScabLDs** and **AppleScabFDs** datasets can be further explored for advanced disease detection systems using CNNs and transfer learning.

## Conclusion

The fruit datasets available on PapersWithCode represent a diverse ecosystem of resources for researchers and practitioners. They span the entire value chain from growth monitoring to retail applications and cover various computer vision tasks.

While some datasets have generated significant research interest, many others remain underutilized. This presents opportunities for novel research and applications, particularly in:

1. Agricultural technology and automation
2. Food quality assessment
3. Retail and inventory management
4. Computer vision method development

For researchers looking to contribute to these fields, these datasets provide valuable starting points that can lead to impactful innovations in fruit-related technologies. 

## License Types
- **CC BY 4.0**: TomatoPlantfactoryDataset, CherryBBCH72, AppleBBCH81
- **CC BY-NC 4.0**: Embrapa ADD 256
- **MIT License**: Fruits 360
- **U.S. Public Domain**: Multi-species Fruit Flower Detection

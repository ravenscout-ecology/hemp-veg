# READ ME - YT High Elevation Monitoring Program Vegetation Data 2022

#### Data Source for Attribution: Environment and Climate Change Canada

This dataset contains raw vegetation data associated with the High Elevation Monitoring Program (HEMP) run by Environment and Climate Change Canada's Canadian Wildlife Service Northern Region in Whitehorse, Yukon. The data were used in conjunction with bird species data collected using autonomous recording units (ARUs) at the same sample sites to assess the relationships between vegetation and bird abundance. Vegetation data were collected in July and August, 2022.


## DATASET CONTENTS

The dataset contains four CSV files:

YT_HighElevationMonitoringProgram_Veg_2022_Data.csv: The raw vegetation data. 

YT_HighElevationMonitoringProgram_Veg_2022_DataDictionary.csv: All fields used in the dataset with the corresponding table location, field description, and reference to lookup tables as needed.

YT_HighElevationMonitoringProgram_Veg_2022_Lookups.csv: All codes used in the dataset with the corresponding descriptions.

YT_HighElevationMonitoringProgram_Veg_2022_VegetationCodes.csv: All vegetation species codes used in the dataset with the corresponding common and scientific names.


## DATA COLLECTION METHODS

### Study Area

Our study area was located in southern Yukon, specifically in the Coast Mountain Range of the Western Cordillera. It ranged from Kluane National Park in the southwestern corner of Yukon to the Yukon-BC border in central Yukon (from 60.008° to 61.037° N and -138.598° to -134.568° W). Specific sample sites were located on ten mountains in southern Yukon within the St. Elias Mountains, Ruby Ranges, Yukon-Stikine Highlands, and Yukon Southern Lakes ecoregions within the Boreal Cordillera ecozone and Bird Conservation Region 4 (Northwest Interior Forest).

We identified four broad habitat zones on each mountain as outlined in Nagy and Grabherr (2009), Boyle and Martin (2015), and Martin et al. (2021) using regional landcover data (ABoVE landcover for Arctic-Boreal region; Wang et al. 2019) and bioclimate mapping (Yukon Government 2023) to differentiate elevation and vegetation characteristics: (1) low boreal (232-950 m Above Sea Level (ASL), mature conifer or conifer-deciduous forest); (2) high boreal (389-1600 m ASL, mature open conifer forest); (3) subalpine (826-2443 m ASL, an ecotone between the high boreal forest and treeline containing a mix of herb or grass-dominated meadows, shrubs (0.15-10 m height), and sparse patches (<10% cover) of trees or krummholz; and (4) alpine (1201-3077 m ASL, herb or grass-dominated open areas with sparse patches of dwarf or low shrubs (0.15-1.00 m tall)). To improve the accuracy of mapped habitat zones, we verified transition zones from regionally available SPOT orthoimagery (1 m resolution) and manually adjusted habitat zone boundaries at each of our 10 mountains. This manual adjustment was critical in high boreal-subalpine and subalpine-alpine ecotones where sparse and patchy vegetation complicated zone delineation. For the purposes of this study, we restricted our sampling to only include the subalpine and alpine habitat zones, zones that contain high numbers of shrubs and may be at highest risk of habitat loss or change from shrubification.

### Site Selection

To select sampling sites on our ten mountains, we modified an existing hierarchical sampling design created to monitor terrestrial birds in boreal Canada. The Boreal Bird Monitoring Program (BBMP) which optimizes cost, habitat representation, and spatial balance, was implemented in all ecoregions in Yukon, Canada with surveys occurring annually since 2018 in groups of adjacent ecoregions (Van Wilgenburg et al. 2020). We modified the BBMP design and created the High Elevation Monitoring Program (HEMP) design by restricting the sampling frame to (1) mountains in southwest Yukon with a hiking or access trail, and (2) a sampling area of 2 km total width within each of the four habitat zones (low boreal, high boreal, subalpine, alpine) on each mountain (1 km on each side of the hiking/access trail). An access-restricted sampling frame was necessary to provide cost-efficient, reliable, and safe access to diverse, technical mountain terrain. To conduct sampling across elevational gradients at each of our ten mountains and achieve habitat representation and spatial balance, we selected random sample sites within the sampling frame within each habitat zone. Each of the ten mountains had habitat zones wide enough to accommodate five sample sites per habitat zone with a minimum distance of 300 m between sites to minimize the likelihood of sampling the same bird on multiple autonomous recording units (ARUs) (Van Wilgenburg et al. 2020). For the purposes of this research, we used the target sample size of five sample sites in only the subalpine and alpine zones for ten sample sites per mountain and 100 sample sites across all mountains.

### Vegetation Data

Shrubs (woody stemmed vegetation) are characteristic features in Yukon boreal subalpine habitats and predominantly occur as medium (1-2 m) and tall shrubs (2-10 m). In the alpine, shrubs typically occur as low (0.5-1 m) or very low/dwarf varieties (0.15-0.5 m) with the remaining ground cover dominated by herbaceous plants, lichen, and rock (Yukon Ecological and Landscape Classification and Mapping Guidelines; Environment Yukon 2016). We collected vegetation data using ground surveys at each subalpine (n = 50) and alpine (n = 50) sample site during the summer of 2022 using methods adapted from Thompson et al. (2016). We established a 10 m radius plot centered on an autonomous recording unit (ARU) and divided the plot into 4 quarters based on cardinal direction. Shrub measurements were taken within each quarter following a three-step process: First, we characterized shrubs based on height as (1) very low (0.15-0.5 m), (2) low (0.5-1 m), (3) medium (1-2 m), or (4) tall (2-10 m) to ensure even sampling across all shrub heights. We classified all vegetation <0.15m tall as herbs and all vegetation >10m tall as trees (BC Ministry of Forests and Range, 2010). We did not include trees in our sampling procedure. Second, we selected the (1) nearest and (2) second nearest shrub to the ARU in each height category in each quarter. Third, we recorded for each selected shrub: distance from the ARU, height, number of stems in each plant (stem count), species, health (living or dead), capacity to bear fruit, and structure (erect or matted). Vegetation data were collected in collaboration with Environment and Climate Change Canada's Canadian Wildlife Service Northern Region (ECCC CWS-NOR). 


## OTHER RESOURCES

Bird data associated with these sample site locations were processed on the online platform WildTrax and are publicly available on the Government of Canada's Open Data portal: https://open.canada.ca/data/en/dataset/b6897990-5d83-46c0-9e93-3bd7cfde3060

For more information about this dataset, please contact Anna Jacobsen at ravenscoutyt@gmail.com.


## REFERENCES

Boyle WA, Martin K. 2015. The conservation value of high elevation habitats to North American migrant birds. Biological Conservation. 192:461–476. doi:10.1016/j.biocon.2015.10.008

Martin K, Altamirano TA, de Zwaan DR, Hick KG, Vanderpas A, Wilson S. 2021. Avian ecology and community structure across elevation gradients: The importance of high latitude temperate mountain habitats for conserving biodiversity in the Americas. Global Ecology and Conservation. 30:e01799. doi:10.1016/j.gecco.2021.e01799

Nagy L, Grabherr G. 2009. The Biology of Alpine Habitats. Oxford University Press Oxford. doi: 10.1093/oso/9780198567035.001.0001

Thompson SJ, Handel CM, Richardson RM, McNew LB. 2016. When winners become losers: Predicted nonlinear responses of arctic birds to increasing woody vegetation. PLoS One. 11(11). doi:10.1371/journal.pone.0164755

Wang JA, Sulla-Menashe D, Woodcock CE, Sonnentag O, Keeling RF, Friedl MA. 2019. ABoVE: Landsat-derived Annual Dominant Land Cover Across ABoVE Core Domain, 1984-2014. ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/1691

van Wilgenburg SL, Lisa Mahon C, Campbell G, McLeod L, Campbell M, Evans D, Easton W, Francis CM, Haché S, Machtans CS, et al. 2020. A cost efficient spatially balanced hierarchical sampling design for monitoring boreal birds incorporating access costs and habitat stratification. PLoS One. 15(6). doi:10.1371/journal.pone.0234494


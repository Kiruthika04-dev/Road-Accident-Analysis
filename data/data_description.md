# Data Description

## About the Dataset

### Context
The UK government amassed traffic data from 2000 to 2016, recording over 1.6 million accidents during this period. This makes it one of the most comprehensive traffic datasets available. The dataset provides a snapshot of a country undergoing significant change, offering a broad view of traffic accidents and related statistics over the years.

Note that all the accident data is derived from police reports, meaning this dataset excludes minor incidents.

### Content
The dataset consists of several files:

- **`ukTrafficAADF.csv`**: This file tracks the traffic volume on all major roads in the UK from 2000 through 2016. The core statistic in this file is AADT (Average Annual Daily Flow), which measures the activity on a road segment based on the number of vehicle trips that traverse it. For more information about AADT, you can refer to the [AADT Wikipedia page](https://en.wikipedia.org/wiki/Average_annual_daily_traffic).
  
- **Accident Data**: The accident data is split across three CSV files:
  - **`accidents_2005_to_2007.csv`**: Contains accident data for the years 2005 to 2007.
  - **`accidents_2009_to_2011.csv`**: Contains accident data for the years 2009 to 2011.
  - **`accidents_2012_to_2014.csv`**: Contains accident data for the years 2012 to 2014.
  
  Together, these three files contain over 1.6 million traffic accidents. The total time period covered is from 2005 to 2014, but data for the year 2008 is missing.

- **Data Dictionary**: A data dictionary for the entire dataset is available on the UK Department of Transport website. For detailed descriptions of individual columns, please refer to the column metadata.

### Acknowledgements
This dataset is licensed under the [Open Government License](https://www.gov.uk/government/organisations/department-for-transport) used by all data on data.gov.uk. The raw datasets are available for download from the UK Department of Transport website [here](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales).

### Inspiration
The dataset offers many opportunities for analysis and exploration. Some potential questions and analyses include:
- **How has changing traffic flow impacted accident rates over time?**
- **Can we predict accident rates based on traffic flow? What changes might improve accident rates?**
- **Plot interactive maps to visualize trends**, such as:
  - How has London's cycling infrastructure and traffic flow evolved?
  - Which are the busiest roads in the nation?
- **Analyze areas with minimal change**, identify infrastructure needs, and assess the success or failure of previous infrastructure efforts.
- **Compare Rural vs. Urban areas**, considering factors such as road categories (RoadCategory).
- **Analyze regional differences** (England, Scotland, and Wales).
- The dataset also supports analysis of **miles driven**. This can be calculated by multiplying AADF by the corresponding length of the road (link length) and the number of days in the year. What insights can this give about UK road usage?

### Dataset Link
The dataset can be found on Kaggle: [2000-16 Traffic Flow Dataset for England, Scotland, and Wales](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales).

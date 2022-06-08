# Cluster-based-classification_DS1
The dataset provided had eight different which are already important features containing Channel ID, Time stamp, Host ID and other important details of a CDN. Total number of records were 88435. User ID and Channel ID had null values to handle. Goal was to apply pre-processing techniques to minimise errors. The dataset had categorical values which needed a proper encoding technique. One hot encoding was suitable to apply for this situation but unfortunately lead to drastic increase in number of attributes which eventually leads to loss of information. So, the best way was to choose featues according to their histogram frequency. Geo-location feature was altered according to most frequent values based on histogram.
# Experimentation with and without duplicates
Below flowchart gives a brief description of approach used
![DS1_flowchart (1)](https://user-images.githubusercontent.com/80226882/172726069-acb1f178-3a1e-45f7-b4dd-a9ced6efe0ea.png)

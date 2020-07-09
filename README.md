# Library Circulation Data Project

Library circulation or library lending comprises the activities around the lending of library books and other material to users of a lending library. A circulation or lending department is one of the key departments of a library.

This research project aims to find the deciding factors for the library circulation in the San Mateo Public Library.

# Summary

## Datasets Used

[San Mateo County Libraries datasets](https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/SMCL_ANF_Items.csv),  [Demographic data sets from County of San Mateo Datahub](https://datahub.smcgov.org/resource/pkmq-j36i.json)
### Our first goal is to gather and look at the dataset and to filter usable data. We determine which data are useful and dropped the columns we have no use for. We also renamed some of the fields to have a better understanding of our data.

### We look at each library and where each branch belongs to and broke them down by region. We can visually see if each category’s circulation for different region.

<img src = https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/Output/Book%20Categories%20vs%20Total%20Cir%20by%20Region.PNG>

### Then we make a get request to get the Demographic datasets from the County of San Mateo Datahub api.

<img src = https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/Output/San%20Mateo%20Datahub%20API.PNG>

### Then we plotted scatter and linear model for Population versus Library Circulation, Median Age versus Library Circulation and Total Items Library Owned vs Library Circulation.

<img src = https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/Output/Total%20Items%20Library%20Owned%20vs%20Library%20Circulation.PNG>
<img src = https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/Output/Median%20Age%20vs%20Library%20Circulation.PNG>
<img src = https://github.com/Duong-Luu/Library-Circulation-Data-Project/blob/master/Output/Population%20vs%20Library%20Circulation.PNG>

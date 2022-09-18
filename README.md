# Bike Dataset Exploration

## by Maduabuchi Anamelechi


## Dataset

> The Bike Dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

The Columns contained in the datasets are:
> duration_sec
> start_time
> end_time
> start_station_id
> start_station_name
> start_station_latitude
> start_station_longitude
> end_station_id
> end_station_name
> end_station_latitude
> end_station_longitude
> bike_id
> user_type ("Subscriber" = Member, "Customer" = Casual)
> member_birth_year
> member_gender
> bike_share_for_all_trip

### Preliminary Wrangling Steps

To be able to prepare the dataset for analysis, i took the following wrangling steps;

> I found out that some columns has a wrong datatypes and corrected them

> I also seperated the date and time for both start_date and end_time columns into their own seperate columns.

> I dropped the null values in the dataset too.

> Finally i dropped the columns that are not needed for the analysis

## Summary of Findings

It was awesome exploring the relationship between between various features in the dataset. The following findings was made:

> I found out the `duration_sec` column was greatly skewed to the right It was also revealed that there were more riders towards the end of the month It was also revealed that the subscribers were more than the casual constomers while the male gender was way more than others.

> A good number of subscribers don't share bike during their ride.

> The male gender forms a higher percent of the customer types especially the subscribers.

> The casual customers spend more time on their ride than the subscribers.

> Those that didn't specify their gender has the highest average duration time followed by the female gender.

> Those who didnt share their bike during the ride spends a little longer time on the average compared to those who shared their bike during the ride.

> On the average the female gender spend more time on their ride compared to other genders for both customer types.

> Casual customers that didn't share their bike spent more time on their ride.

> Those who didnt specify their gender and didnt share their bike spent more time during their ride.


## Key Insights for Presentation

> Taking a look at the `duration` column in minutes, we found out that it has a unimodal distribution with a peak at the 10th minute showing that a rider spends an average of 10mins on their ride.

> Also examining the type of customers we have, it has been revealed that we have more subscribers than casual customers. The subcribers makes up about 89% of our customer base. This led to further deep dive analysis as seen in the presentation slide.
# Mobile-phone-Signaling-Data
##  Description
This dataset was collected by volunteers from October 2021 to November 2021 with GPS trajectory data and MSD.Each row of data contains the latitude and longitude of the GPS and the base station connected when the mobile phone signaling is generated, wherein the latitude and longitude of the GPS can be used as the real position, and the latitude and longitude of the base station connected to the mobile phone is the position in the signaling data of the mobile phone. For privacy protection, we deleted the volunteer id, which does not affect the research on the trace matching of mobile phone signaling data.

DAYS,TIMES: the timestamp of the Mobile phone signaling data

"LAT": latitude of GPS, in wgs84.

"LNG": longitude of GPS, in wgs84.

"CELLLAT": latitude of cell tower which the phone is presently connected to.

"CELLLNG": longitude of cell tower which the phone is presently connected to.


## Citation
If you publish work based on, or using, this dataset, we would appreciate citations to the following:
@inproceedings{Mobile-phone-Signaling-Data,
  author    = { Huang, Yulang; Wang, Dianhai; Xu, Wang; Cai, Zhengyi},
  title     = { Accurate Map Matching Method for mobile phone signaling data under Spatio-temporal Uncertainty}
  year      = {2023},
}


##License

This library is licensed under the CC-BY-4.0 License.

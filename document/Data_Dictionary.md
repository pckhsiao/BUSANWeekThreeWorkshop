# Data Dictionary

# Dataset: week3_DimRegion.csv

| Variable | Description |
|-----------|-------------|
| RegionId | Unique identifier assigned to each region |
| Region | Region of the crash location based on territorial local authority boundaries |
| Country | Country of the crash location |

---

# Dataset: week3_FactCrash.csv

| Variable | Description |
|-----------|-------------|
| Year | Year-end date representing the year in which the crash occurred |
| RegionId | Unique identifier assigned to each region |
| Location | Description of the crash location |
| MinorInjuryCount | Number of minor injuries associated with the crash |
| SeriousInjuryCount | Number of serious injuries associated with the crash |
| FatalCount | Number of fatal casualties associated with the crash |
| Car | Number of cars, station wagons, SUVs, vans, and/or utes involved in the crash |
| Truck | Number of trucks involved in the crash |
| Bus | Number of buses involved in the crash, excluding school buses |
| SchoolBus | Number of school buses involved in the crash |
| Moped | Number of mopeds involved in the crash |
| Moped | Number of motorcycles involved in the crash |
| Bicycle | Number of bicycles involved in the crash |
| Pedestrian | Number of pedestrians involved in the crash, including users of skateboards, scooters, and wheelchairs |
| Object | Object struck during the crash, examples include `Cliff or Bank`, `Guard Rail`, `Building`, `Parked Vehicle`, and `Traffic Sign` |
| TrafficControl | Traffic control at the crash site, examples include `Traffic Signals`, `Stop Sign`, `Give Way Sign`, and `Pointsman` |
| StreetLight | Street lighting status, values include `On`, `Off`, `None`, or `Null` |
| SpeedLimit | Speed limit applying at the crash location |
| RoadCharacter | General nature of the road, examples include `Bridge`, `Motorway Ramp`, and `Rail xing` |
| RoadSurface | Road surface description at the crash site, values include `Sealed` and `Unsealed` |
| FlatHill | Road gradient classification, values include `Flat` and `Hill` |
| NumberOfLanes | Number of lanes on the crash road |
| Holiday | Type of public holiday on the day of the crash |
| Light | Lighting conditions at the time of the crash, values include `Bright Sun`, `Overcast`, `Twilight`, `Dark`, and `Unknown` |
| Weather | Weather conditions at the time of the crash, examples include `Fine`, `Mist`, `Light Rain`, and `Heavy Rain` |

---

# Dataset: week3_FactOffence.csv

| Variable | Description |
|-----------|-------------|
| Period | Month-end date representing the month and year |
| RegionId | Unique identifier assigned to each region |
| RedLightCount | Number of red-light offences detected and issued by police officers |
| RedLightMoney | Revenue received from red-light offences |
| AlcoholCount | Number of offences relating to driving under the influence of alcohol |
| AlcoholMoney | Revenue received from alcohol-related offences |
| MobileCount | Number of offences relating to the use of handheld devices while driving |
| MobileMoney | Revenue received from mobile phone offences |
| SpeedCount | Number of speeding offences detected by police officers |
| SpeedMoney | Revenue received from speeding offences detected by police officers |

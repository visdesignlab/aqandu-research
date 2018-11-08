
![Estimated PM2.5 concentration at 6:00 pm (left panel) and 9:30 pm (right panel) on July 4, 2018.](images/wildfire.png)

[AQ&U Citizen Website](https://aqandu.org)

## Synopsis

A low-cost, efficient pollution monitoring embedded system is currently under design by the electrical engineering team. The goal is a device that does not significantly sacrifice accuracy of PM concentration measurement for a small, low-cost, low-power footprint. Each station is fully self-contained, and is capable of relaying data about its environment to a cloud storage at an arbitrarily rapid rate. The stations will be distributed across Salt Lake City through a citizen science engagement effort.
The computer science team will stream the measurements into a statistical modeling system to estimate PM levels across Salt Lake City. This system will combine sensor measurements with land-use information to produce accurate, real-time estimates and fine-grained resolutions. The estimates will be communicated to the public through a web-based visualization interface. This interface will include advanced functionality to support individualized sense-making of PM exposures.

The combined system will be a reliable and scalable cyber-physical framework for estimating air quality at a fine-grain in both space and time, coupled with fundamental breakthroughs in low-cost sensing, reliable modeling of environmental factors, and communication of air quality to the public. The proposed system should demonstrate the following:
1. flexible, general, integrated approach to acquiring PM measurements with varying degrees of density/accuracy/reliability,
2. incorporating land use, topographic data, and weather data, with sensor measurements
3. estimates of air quality with relatively high resolution in space and time,
4. validated with quantifiable estimates of expected error,
5. reasonable expectations of privacy for citizen- based monitoring stations, and
6. a responsive visualization-based API that can communicate estimates of PM levels and error estimates for any point in the Salt Lake Valley over a defined historical period.



## Personnel

- Meyer, Miriah PD/PI
- Gaillardon, Pierre-Emmanuel Co PD/PI
- Kelly, Kerry Co PD/PI
- Whitaker, Ross Co PD/PI
- Goffin, Pascal Postdoctoral (scholar, fellow or other postdoctoral position)
- Becnel, Tom Graduate Student (research assistant)
- Biglari, Amir Graduate Student (research assistant)
- Sahay, Tofigh Graduate Student (research assistant)
- Hopkins, Aspen Undergraduate Student
- Taylor, Trenton Undergraduate Student
- Tingey, Kyle Undergraduate Student



## Collaborators

- Butterfield, Tony



## Publications

### Journals or Juried Conference Papers

- K. Le, K. Tingey, T. Becnel, P. Giallardon, T. Butterfield/K. Kelly Building Air Quality Sensors & Citizen Scientists, Chemical Engineering Education. Status = ACCEPTED.

### Other Conference Presentations / Papers
- P. Goffin, A. Hopkins, W. Willett, M Meyer. Challenges in Urban Air Quality Data Visualization. Proceedings of the IEEE VIS Workshop on Urban Data Visualization (CityVis).  Status = ACCEPTED
- K. Kelly, T. Sayahi, A. Petty, A. Butterfield (2017). Evaluation of the Plantower PMS Low-Cost Particulate Matter Sensor. Air Quality: Science for Solutions. Salt Lake City, UT. Status = PUBLISHED
- T. Sahay, T. Butterfield, K. Kelly (2017). Laboratory and Field Calibration of a Low-Cost Particulate Matter Sensor. AAAR Annual Meeting. Raleigh, NC. Status = PUBLISHED
Aspen Hopkins, Pascal Goffin, Miriah Meyer (2017). Particulates Matter: Assessing Needs for Air Quality Visualization. IEEE VIS. Status = PUBLISHED



## Code


- Frontend; [Link](url)
- Modeling: [Link](url)
- Backend: [Link](url)
- airU design files: [Link](url)



## Educational activities

get from report



## Outreach

National efforts to disseminate the results included invited talks at US Ignite and MPSoC, and presentations at the annual meetings of AAAR, INEF, Utah Science for Solutions, Annual Utah Air Quality Conference, U.S. Ignite, Utah Ignite, ASEE, Colorado State University. We also presented internationally at City, University of London. The output of the modeling system is both available online and in the form of animations that are used regularly by the team to present these results to broader audiences.

The team continues to actively perform community outreach, with an emphasis on engaging under-served areas. The local outreach venues included several community council meetings, a TechTalk at the city library, several media interviews, two community events at libraries in underserved communities, and an invited talk at the Utah Council of Engineers. These outreach activities have led to many more host volunteers than the project can support. However, it does allow us to have a rich set of choices for placing sensors in regions where the uncertainty is the highest.



## Broader impact outcomes

The work realized for the Gen2 board advances the field of low-cost air quality monitoring by creating an affordable system. It is the first time a versatile system (supporting all important measurements targeted by the project but also more through extension ports) is realized. The project is also gathering an unprecedented amount particulate matter concentration information that will enable us to understand low-cost sensor performance as well as to understand spatiotemporal patterns in particulate matter pollution. Furthermore, the project is identifying new ways that residents would like to engage with air quality data, leading to novel visualization design ideas.

The Gen2 system has already received a lot of attention through local outreach communities and asthma study communities. A start-up company, Tetrad: Sensor Network Solutions, LLC, has been created with the objective to fulfill the AirU sensors to local communities and research groups. Tetrad has deployed 150 devices in homes around the valley through the PRISMS research group—a asthma study group. 10 AirU devices have been sold to a professor at Utah State University, who has used them for air quality studies in Palestine, as well as the Logan valley.

Our preliminary results suggest that air quality is generally poorer in under-served communities in the Salt Lake Valley, and this information is critical as the state plans to place two new projects in this area, a new prison and an inland port. This type of baseline information will be extremely useful for policy makers as they attempt to understand and address air quality impacts from these projects.

The space/time models provide visualizations that allow broader audiences to appreciate the behavior of air-quality in the air shed. Events such as fireworks (on holidays), inversions, or wildfires have spatiotemporal patterns that can be better understood when seeing the evolving estimates of PM concentrations (and associated uncertainties). This understanding is impacting the broader discussion about air quality both in terms of individual behavior and policies that affect air quality in the Salt Lake Valley. The created system has broad impact on disciplines related to air quality studies as the system can be used to gather a large number of data at real-time and at low-cost.

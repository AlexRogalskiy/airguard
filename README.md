# Airguard

This platform is a personal project for monitoring and processing air pollution data obtained from
a network of sensors owned and maintained by https://airly.eu, which I am not affiliated with in any way.
Data is harvested from the API published by the company at https://developer.airly.eu and remains
the property of Airly sp. z o.o., Kraków, Poland.

The platform is intended to be deployed using various Amazon Web Services. Due to the focus of the project
being education and experimentation, some solutions may seem overengineered if you're browsing through
the code. You're welcome to use any and all parts of it in whatever manner you see fit, as long as you
adhere to Airly's [Terms of Service](https://airly.eu/docs/tos-en.pdf) and appropriate usage limits
when using their API.

### Problem statement

My home city of Kraków has been suffering for a long time from high levels of air pollution, specifically
particulate matter (PM2.5/PM10). The problem is mainly caused by emissions from outdated heating systems
in the winter, and compounded by the city's unfavourable location in a geological basin, where the surrounding
hills limit airflow throughout the city. The battle to mitigate that problem is being fought on several fronts,
one of which is education and information. To that end, a startup named Airly arose in the late 2016,
with the aim of developing and deploying a fine-grained network of low-cost, network-enabled pollution sensors,
data from which would be easily accessible to general public in real time. Today, Airly has hundreds of sensors
across Poland, and is starting the expansion to foreign cities.

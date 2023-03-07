#  OBD Play

<a id='overview'></a>
## Overview
**OBD Play** is a SwiftUI iPhone application for viewing Ford Mustang Mach-E trip and charge data recorded with the companion OBD Record application.

## Table of Contents
- [Overview](#overview)
- [What's new](#whats-new)
- [Requirements](#requirements)
- [Installation](#installation)
- [Privacy Notice](#privacy)
- [Trips](#trips)
- [Charges](#charges)
- [Settings](#settings)

<a id='whats-new'></a>
## What's new
- Everything is new at this point, just explore the data and let us know of any problems.

<a id='requirements'></a>
## Requirements
- Apple iPhone running iOS 16.2 or later
- InfluxDB data source to supply vehicle data (a sample data source is proviced for testing or you can create your own at [Influx Cloud](https://cloud2.influxdata.com/signup))

<a id='installation'></a>
## Installation
The beta test releases as being distributed by the Apple TestFlight application.  If you receive an invitation or a shared download link you can access OBD Play from the TestFlight app.

<a id='privacy'></a>
## Privacy Notice
OBD Play does not collect or share any personal information or data.

OBD Play may use your Vehicle Identification Number (VIN) to access your vehicle trip and charging data in a database created and controlled by you.

<a id='trips'></a>
## Trips
The Trips tab displays a list of the trips made in a selected time period along with a summary of the distance and evergy used durin this period.

![Trips](https://github.com/sillygoose/obd-play/blob/images/images/Trips.png)

A trip records the vehicle dsta from the shift selector leaving the Park position until it returns back to Park and the detailed trip view displays a map of the roure taken, the elevation profile of the trip, and interesting details of the trip.

![Trip Detail](https://github.com/sillygoose/obd-play/blob/images/images/Trip%20Detail.png)

<a id='charges'></a>
## Charges
The Charges tab displays a list of charges in the selected period along with the energy pulled from the charger and the energy deliverd to the high-voltage battery.
![Charges](https://github.com/sillygoose/obd-play/blob/images/images/Charges.png)

You can select a charge from the list and see the details of the charge with information from:
- charger data
- environmental data
- energy use
- high-voltage battery data

![Charge Detail](https://github.com/sillygoose/obd-play/blob/images/images/Charge%20Detail.png)

<a id='settings'></a>
## Settings
The Settings tab manages the selection of vehicles, data sources, and other useful features including:
- save/restore settings
- manage data sources
- manage vehicles
- manage locations


![Settings](https://github.com/sillygoose/obd-play/blob/images/images/Settings.png)

# OBD Play

## Table of Contents
- [Overview](#overview)
- [What's new](#whats-new)
- [Requirements](#requirements)
- [Installation](#installation)
- [Privacy Notice](#privacy)
- [Trips](#trips)
- [Charges](#charges)
- [Settings](#settings)

<a id='overview'></a>
## Overview
**OBD Play** is a iPhone application for viewing Ford Mustang Mach-E trips and charge sessions recorded by the companion **OBD Record** application.

<a id='whats-new'></a>
## What's new
- adds trip spotlights for viewing preconditioning and temperatures
- adds a charge spotlight for viewing charge session power and temperatures
- charges now show battery age and the battery State of Health (SoH) graphs show both odometer and age for the x-axis
- everything is new and in a state of flux, just explore and report any problems or share your feedback

<a id='requirements'></a>
## Requirements
- Apple iPhone running iOS 16.2 or later
- InfluxDB data store to supply vehicle data (you can create your own at [Influx Cloud](https://cloud2.influxdata.com/signup))

<a id='installation'></a>
## Installation
The beta test releases are being distributed using the Apple TestFlight application.  If you receive an invitation or have accrss to a shared download link you can install **OBD Play** from the TestFlight app and share crash reports and screenshots to help improve the aoftware.

<a id='privacy'></a>
## Privacy Notice
**OBD Play** does not collect or share any personal information or data.

**OBD Play** uses your Vehicle Identification Number (VIN) to access your vehicle trip and charging data in a data store created and controlled by you and is not shared outside the application.

<a id='trips'></a>
## Trips
The Trips tab displays a list of the trips made in a selected time period along with a summary of the distance, evergy used, and efficiency during this period.

A trip records vehicle dsta from the shift selector leaving the Park position until it returns back to Park and the detailed trip view displays:
- map of the route
- elevation profile
- start and end points with the ability to add point of interest (POI) details
- energy use and efficiency
- speed and position data
- high voltage battery data

<img width="800" alt="image" src="https://raw.githubusercontent.com/sillygoose/obd-play/main/images/Trips.png">

The Trips spotlight includes graphs of efficiency/temperature, monthly efficiency, and more over all your trips.  The detailed trip spotlight displays insights into the data for a particular trip.

<a id='charges'></a>
## Charges
The Charges tab displays a list of charges in the selected period along with the energy pulled from the chargers, the energy delivered to the high voltage battery, and the overall charging efficiency.

You can select a charge from the Charges list and see the details of the charge with information from:
- location, duration, and charger type
- power and energy data
- high voltage battery details including the State pf Charge (SoC) and State of Health (SoH)

<img width="800" alt="image" src="https://raw.githubusercontent.com/sillygoose/obd-play/main/images/Charges.png">

The Charging spotlight includes graphs of energy use and the battery SoH. Each detailed charge spotlight displays graphical insights for a particular charging session.

<a id='settings'></a>
## Settings
The Settings tab manages the selection of vehicles, data stores, and other useful features including:
- save/restore settings
- manage data stores
- manage vehicles
- manage location data
- help for various **OBD Play** features
- **OBD Play** version and other application information

<img width="400" alt="image" src="https://raw.githubusercontent.com/sillygoose/obd-play/main/images/Settings.png">

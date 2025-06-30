# UPAS-environmental-data
Work environment UPAS-measurments at three different places at Karolinska Institutet

## Description  
The provided data was produced during a one-week period from three different locations:
* PCR clean-room
* Samples reception room
* BD COR instrument room

## Device
[UPAS 2.1](https://www.accsensors.com/upasv2.1plus)
## Type of measurments from the UPAS without filters
| Type | Name | Unit |
| :------------------- | :----------: | ----------: |
| DateTime | SampleTime|(HH:MM:SS)|
| DateTime | UnixTime|(s)|
| DateTime | DateTimeUTC|(YYYY-MM-DDTHH:MM:SS) (UTC date time format)|
| DateTime | DateTimeLocal|(YYYY-MM-DDTHH:MM:SS) (Local date time format)|
| FilterSample | PumpingFlowFactory|(L*min^-1)|
| FilterSample | OverallFlowFactory|(L*min^-1)|
| FilterSample | SampledVolumeFactory|(L)|
| FilterSample | PumpingFlowOffset|(L*min^-1)|
| FilterSample | OverallFlowOffset|(L*min^-1)|
| FilterSample | SampledVolumeOffset|(L)|
| FilterSample | FilterDP|(Pa)|
| Battery | BatteryCharge|(%)|
| Atmo | AtmoT|(C)|
| Atmo | AtmoP|(hPa)|
| Atmo | AtmoRH|(%RH)|
| Atmo | AtmoDensity|(g*L^-1)|
| Atmo | AtmoAlt|(m ASL)|
| GPS | GPSQual|(-)|
| GPS | GPSlat|(decimalDegree)|
| GPS | GPSlon|(decimalDegree)|
| GPS | GPSalt|(m)|
| GPS | GPSsat|(integer)|
| GPS | GPSspeed|(m*s^-1)|
| GPS | GPShDOP|(-)|
| Motion | AccelX|(mg)|
| Motion | AccelXVar|(mg)|
| Motion | AccelXMin|(mg)|
| Motion | AccelXMax|(mg)|
| Motion | ----------:|(mg)|
| Motion | AccelYVar|(mg)|
| Motion | AccelYMin|(mg)|
| Motion | AccelYMax|(mg)|
| Motion | AccelZ|(mg)|
| Motion | AccelZVar|(mg)|
| Motion | AccelZMin|(mg)|
| Motion | AccelZMax|(mg)|
| Motion | AccelComplianceCnt|(#)|
| Motion | AccelComplianceHrs|(hrs)|
| Motion | Xup|(%)|
| Motion | XDown|(%)|
| Motion | Yup|(%)|
| Motion | Ydown|(%)|
| Motion | Zup|(%)|
| Motion | Zdown|(%)|
| Motion | StepCount|(#)|
| Light | ----------:|(lux)|
| Light | UVindex|(-)|
| Light | HighVisRaw|(-)|
| Light | LowVisRaw|(-)|
| Light | IRRaw|(-)|
| Light | UVRaw|(-)|
| PMSensor | PMMeasCnt|(#)|
| PMSensor | PM1MC|(ug*m^-3)|
| PMSensor | PM1MCVar|(ug*m^-3)|
| PMSensor | PM2_5MC|(ug*m^-3)|
| PMSensor | PM2_5MCVar|(ug*m^-3)|
| PMSensor | PM0_5NC|(#*cm^-3)|
| PMSensor | PM1NC|(#*cm^-3)|
| PMSensor | PM2_5NC|(#*cm^-3)|
| PMSensor | PMtypicalParticleSize|(um)|
| PMSensor | PM2_5SampledMassFactory|(ug)|
| PMSensor | PM2_5SampledMassOffset|(ug)|
| EngData | U12T|(C)|
| EngData | U29T|(C)|
| EngData | FdpT|(C)|
| EngData | AccelT|(C)|
| EngData | U29P|(hPa)|
| EngData | PumpPow1|(integer)|
| EngData | PumpV|(V)|
| EngData | MassFlowFactory|(g*min^-1)|
| EngData | MFSVout|(V)|
| EngData | BattVolt|(V)|
| EngData | v3_3|(V)|
| EngData | v5|(V)|
| EngData | Charging|(bool)|
| EngData | ExtPow|(bool)|
| EngData | FLOWCTL|(s)|
| EngData | GPSRT|(s)|
| EngData | SD_DATAW|(s)|
| EngData | SD_HEADW|(s)|
| Gas | CO2|(ppm)|
| Gas | SCDT|(C)|
| Gas | SCDRH|(%)|
| Gas | VOCRaw|(-)|
| Gas | NOXRaw|(-)|

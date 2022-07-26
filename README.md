# PC2_DataAnalysis
Allows you to get live data from your drives in Project Cars 2 in .csv format. Then open it with Apaix, a data visualization tool from TeKshift.

Hi all, ever wanted to analyse your own data as a motorsport engineer?

I programmed this easy c++ software that allows you to get the data lap by lap in .csv.
Then its easy for you to visualize them via excel, matlab or even better : Apaix, available for free.

Apaix has been developped by motorsport engineer to vizualise data, and has a nice palmares (as used on the quickest electric bike of the world).
I highly encourage you to go on https://www.tekshift.de/apaix-data-software and try it.

I have no name at this time for the SW, so feel free to offer !

# Setup of PC2_DataAnalysis
1) Install the SW via the .exe file
2) Create a folder C:\temp\Apaix this is where the .csv data file will be created.
3) Launch project cars 2 and go to option--> activate shared memory PC2
4) Start to play and launch PC2_DataAnalysis
5) A popup windows will opened, keep it opened while you play. To close it, click on it or on the cross to close it.
6) Load the data in apaix.

# Tested
1) Free practice
2) Online races

# Coming Soon
- Explaination on Apaix
- My Apaix layout
- Any of your requests !

# Data retrieved:
Time : (s) time elapsed since last lap
mBrake : (%) brake pedal position
mBoostAmount : (%) boost
mEngineTorque : (Nm) engine torque
mLocalAccelerationLat : (m.s-2) car lateral acceleration
mLocalAccelerationUp  : (m.s-2) car vertical acceleration
mLocalAccelerationLong  : (m.s-2) car longitudinal acceleration
mOrientation[VEC_X]  : not sure, certainly euler angles
mOrientation[VEC_Y]   : not sure, certainly euler angles
mOrientation[VEC_Z]   : not sure, certainly euler angles
mLocalVelocityLong : (m.s-1) car longitudinal speed
mLocalVelocityUp : (m.s-1) car vertical speed
mLocalVelocityLat : (m.s-1) car lateral speed
mGear : gear engaged
mSpeed : (kph) vehicule speed
mOdometerKM : (km) odometer
mTyreTempFL : (°C) Front left tyre temperature
mTyreTempFR : (°C) Front right tyre temperature 
mTyreTempRL : (°C) Rear left tyre temperature 
mTyreTempRR : (°C) Rear right tyre temperature 
mSuspensionTravelFL : (mm) Front left suspension travel 
mSuspensionTravelFR : (mm) Front right suspension travel  
mSuspensionTravelRL : (mm) Rear left suspension travel  
mSuspensionTravelRR : (mm) Rear right suspension travel  
mBrake : (%) Brake pedal position
mThrottle : (%) Throttle pedal position 
mClutch : (%) Clutch pedal position 
mSteering : (%) Steering position <0 = left >0 right
mEngineSpeed : (rpm) engine speed
mUnfilteredThrottle : (%) Throttle pedal position unfiltered 
mUnfilteredBrake : (%) Brake pedal position unfiltered 
mUnfilteredSteering : (%) Steering position <0 = left >0 right unfiltered
mWorldPositionLat : (no idea, degree?) Car latitude position
mWorldPositionAlt : (no idea, meters?) Car altitude position 
mWorldPositionLong  : (no idea, degree?) Car longitude position
mSuspensionVelocityFL : (no idea) Rate of change of pushrod deflection Front left
mSuspensionVelocityFR : (no idea) Rate of change of pushrod deflection Front right
mSuspensionVelocityRL : (no idea) Rate of change of pushrod deflection Rear left
mSuspensionVelocityRR : (no idea) Rate of change of pushrod deflection Rear right
mBrakeBias: (%) brake bias, e.g. 40 means 40% on the front.
mTyreTreadTempFL : (°C) Front left tyre tread temperature
mTyreTreadTempFR : (°C) Front right tyre tread temperature 
mTyreTreadTempRL : (°C) Rear left tyre tread temperature 
mTyreTreadTempRR : (°C) Rear Right tyre tread temperature 
mTyreLayerTempFL : (°C) Front left tyre layer temperature 
mTyreLayerTempFR : (°C) Front right tyre layer temperature  
mTyreLayerTempRL : (°C) Rear left tyre layer temperature  
mTyreLayerTempRR : (°C) Rear Right tyre layer temperature  
mTyreCarcassTempFL : (°C) Front left tyre carcass temperature  
mTyreCarcassTempFR : (°C) Front right tyre carcass temperature  
mTyreCarcassTempRL : (°C) Rear left tyre carcass temperature  
mTyreCarcassTempRR : (°C) Rear Right tyre carcass temperature 
mTyreRimTempFL : (°C) Front left tyre rim temperature  
mTyreRimTempFR : (°C) Front right tyre rim temperature  
mTyreRimTempRL : (°C) Rear left tyre rim temperature   
mTyreRimTempRR : (°C) Rear Right tyre rim temperature  
mTyreInternalAirTempFL : (°C) Front left tyre internal air temperature  
mTyreInternalAirTempFR : (°C) Front right tyre internal air temperature  
mTyreInternalAirTempRL : (°C) Rear left tyre internal air temperature 
mTyreInternalAirTempRR : (°C) Rear Right tyre internal air temperature   
mTyreWearFL : (%) Front left tyre wear
mTyreWearFR : (%) Front right tyre wear 
mTyreWearRL : (%) Rear left tyre wear 
mTyreWearRR : (%) Rear right tyre wear 
mBrakeTempCelsiusFL : (°C) Front left brake temperature
mBrakeTempCelsiusFR : (°C) Front right brake temperature 
mBrakeTempCelsiusRL : (°C) Rear left brake temperature 
mBrakeTempCelsiusRR : (°C) Rear right brake temperature 
mAntiLockActive : (boolean) ABS active
mTyreRPSFL : (RPM) Front left wheel speed
mTyreRPSFR : (RPM) Front right wheel speed 
mTyreRPSRL : (RPM) Rear left wheel speed 
mTyreRPSRR : (RPM) Rear right wheel speed 



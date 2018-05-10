# SunPositionCalculator
Simple python sun position calculator. Returns the sun elevation angle (SEA) and azimuth angle (AZ) using the following parameters: latitude, longitude and UTC offset.
You can test it returns the correct values in the following links <a href="https://keisan.casio.com/exec/system/1224682331">Keisan</a> or 
<a href="http://www.pveducation.org/pvcdrom/properties-of-sunlight/sun-position-calculator">PVEducation</a>.
Use cases: Align solar panel angle for maximum sun exposure, intelligent curtain that avoids direct sunlight, etc. 
<br><br>
Take into account this: 
<br>
The above equation only gives the correct azimuth in the solar morning so that:
<br>
Azimuth = Azi, for LST <12 or HRA < 0
<br>
Azimuth = 360° - Azi, for LST > 12 or HRA >0
<hr>
<a href="http://answers.google.com/answers/threadview/id/782886.html">Algorithm source</a>

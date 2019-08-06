#  calanus_diapause_depth 

<b>R source code and data for analyses of <i>Calanus</i> depth distribution during diapause.</b>

<b>all.dat.rda</b>: R-data file with pan-arctic abundance data of <i>Calanus glacialis</i> and <i>Calanus hyperboreus</i> compiled from multiple sources.<br>

The following information is included (column number):<br>
#1: Sampling year<br>
#2: Sampling month<br>
#3: Sampling day (day of month)<br>
#4: Julian day (1-365)<br>
#5: Decimal latitude<br>
#6: Decimal longitude (negative values for western hemisphere)<br>
#7: Upper sampling depth<br>
#8: Lower sampling depth<br>
#9: Bottom depth at station<br>
#10: Sampling gear<br>
#11: Sampling mesh<br>
#12: Dataset ID<br>
#13: Dataset<br>
#14-20: Depth-specific C.glacalis abundance data (ind./m3) per copepodid stage C1-C5 and adult females and males (C6f/m)<br>
#21-27: Depth-specific C.hyperboreus abundance data (ind./m3) per copepodid stage C1-C5 and adult females and males (C6f/m)<br>
#28-35: Depth-integrated C.glacalis abundance data (ind./m2)<br>
#36-43: Depth-integrated C.hyperboreus abundance data (ind./m2)<br>
#44-45: Summed species specific abundances (ind./m3)<br>
#46-47: Summed species specific abundances (ind./m2)<br>
#48-61: Depth-specific abundance data (columns 13-26) corrected for body width/mesh size ratio<br>


<b>analyses_calanus_depth.r</b>: R-script for analyses of <i>Calanus</i> depth distribution.

Additional files:<br>
<b>data_sources.pdf</b>: List of data sources with relevant references (if available) and temporal and spatial data coverage.<br>
<b>arcticmap.r</b>: R-script to plot polar-centered maps.

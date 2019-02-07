#  calanus_diapause_depth 

<b>R code and data file for analyses of <i>Calanus</i> depth distribution during diapause.</b>

<b>all.dat.rda</b>: R-data file with pan-arctic abundance data of <i>Calanus glacialis</i> and <i>Calanus hyperboreus</i> compiled from multiple sources.
The following information is included (column number):
#1: Sampling year
#2: Sampling month
#3: Sampling day (day of month)
#4: Julian day (1-365)
#5: Decimal latitude 
#6: Decimal longitude (negative values for western hemisphere)
#7: Upper sampling depth
#8: Lower sampling depth
#9: Bottom depth at station
#10: Sampling gear
#11: Sampling mesh
#12: Dataset 
#13-19: Depth-specific C.glacalis abundance data (ind./m3) per copepodid stage C1-C5 and adult females and males (C6f/m)
#20-26: Depth-specific C.hyperboreus abundance data (ind./m3) per copepodid stage C1-C5 and adult females and males (C6f/m)
#27-34: Depth-integrated C.glacalis abundance data (ind./m2)
#35-42: Depth-integrated C.hyperboreus abundance data (ind./m2) 
#43-44: Summed species specific abundances (ind./m3)
#45-46: Summed species specific abundances (ind./m2)
#47-60: Depth-specific abundance data (columns 13-26) corrected for body width/mesh size ratio 


<b>analyses_calanus_depth.r</b>: R-script for describing and analyzing the compiled <i>Calanus</i> data in all.dat.rda, with focus on depth distribution during diapause.

Additional files:
<b>data_sources.pdf</b>: List of all <i>Calanus</i> data sources with relevant references (if available) and temporal and spatial data coverage.
<b>data_sources.pdf</b>: R-script to plot polar-centered maps.

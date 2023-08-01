# Methodology-of-a-Large-Scale-Bicycle-Exposure-Estimation

## Md Mintu Miah1, Julia Griswold2, Frank Proulx3, John Bigham4,  Offer Grembek5

1Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: mmmiah@berkeley.edu, ORCID: 0000-0001-6073-3896, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.  

2Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: juliagris@berkeley.edu, ORCID: 0000-0002-1125-3316, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.

3Frank Proulx Consulting, LLC, Email: frank@frankproulxconsulting.com, ORCID: 0000-0001-5157-0300, Address: 343 Trailview Road, Encinitas, CA 92024 

4Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: jbigham@berkeley.edu, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.  

5 Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: grembek@berkeley.edu, ORCID: 0000-0003-1869-9457, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382

## ABSTRACT 

Large-scale network design, safety, and crash estimates largely depend on networkwide bicycling exposure estimation. Previous studies developed direct demand models on a small scale (e.g., city or county) where exposure count and seasonality did not vary widely between count locations. The applicability of such a smaller-scale method is questionable for large-scale applications. This study aims to develop a technique that can be implemented in large-scale bicycle exposure estimation. The study considered the entire state of California as the methodology implementation and used data from 203 unique permanent counters to develop three different types of expansion factors: Hour of Day (HOD) for both weekdays and weekends, Day of Week (DOW), and Month of Year (MsOY) factors. The developed expansion factors were applied for imputing 2589 (3560 legs) short-term site locations to estimate Annual Average Daily Bicycle Traffic (AADBT). Finally, estimated AADBT from both permanent and short-term sites was used to develop a Poisson and Random Forest (RF) regression model. The results indicate that the RF model performs (RMSE=132) better than the Poisson regression model (RMSE=173). RF model RMSE is 85 for low (<52 AADBT) and 58 for mid-volume sites (52-137 AADBT); however, high-volume sites (>137 AADBT) are overestimated with high RMSE (199). The results also indicate that Strava commute, leisure trips, bike, and vehicle ownership status, population and housing density, slope, speed, and nearby universities are crucial predictors of AADBT estimation. The developed methodology will provide guidelines for large-scale network-wide bicycle exposure estimation to the planners and engineers.

# Keywords: Bicycle, Exposure, Strava, Seasonality, Factor, Short-term, Counters

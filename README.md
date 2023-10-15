# Methodology of a Large-Scale Annual Average Daily Bicycle Traffic (AADBT)Estimation 

## Md Mintu Miah1, Julia Griswold2, Frank Proulx3, John Bigham4, Ipsita Banerjee5,  Offer Grembek6

1Postdoctoral Researcher, Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: mmmiah@berkeley.edu, ORCID: 0000-0001-6073-3896, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.  

2Co-director, Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: juliagris@berkeley.edu, ORCID: 0000-0002-1125-3316, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.

3Frank Proulx Consulting, LLC, Email: frank@frankproulxconsulting.com, ORCID: 0000-0001-5157-0300, Address: 343 Trailview Road, Encinitas, CA 92024 

4GIS Specialist, Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: jbigham@berkeley.edu, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.  

5Research Data Analyst, Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: ipsita@berkeley.edu, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382, USA.  


6 Co-director, Safe Transportation Research and Education Center (SafeTREC), University of California, Berkeley, Email: grembek@berkeley.edu, ORCID: 0000-0003-1869-9457, Address: 2150 Allston Way, Suite 400 Berkeley, CA 94704-1382


## ABSTRACT 

Large-scale network design, safety, and crash estimates largely depend on networkwide bicycling volume estimation. Previous studies developed direct demand models on a small scale (e.g., city or county) where bicycle count and seasonality did not vary widely between count locations. The applicability of such a smaller-scale method is questionable for large-scale applications. This study aims to develop a technique that can be implemented in large-scale bicycle volume estimation. The study considered the entire state of California as the methodology implementation and used data from 203 unique permanent counters to develop three different types of expansion factors: Hour of Day (HOD) for both weekdays and weekends, Day of Week (DOW), and Month of Year (MOY) factors. The developed expansion factors were applied for imputing 2589 (3560 legs) short-term site locations to estimate Annual Average Daily Bicycle Traffic (AADBT). Finally, estimated AADBT from both permanent and short-term sites was used to develop a Poisson and Random Forest (RF) regression model. The results indicate that the RF model performs (RMSE=120) better than the Poisson regression model (RMSE=171). RF model RMSE is 59 for low (≤100 AADBT) and 92 for mid-volume sites (101-300 AADBT); however, high-volume sites (>300 AADBT) are overestimated with high RMSE (264). The results also indicate that Strava volume, bike and vehicle ownership status, intersection density, urban/rural status, location of bike parking, and subway station are crucial predictors of AADBT estimation. The developed methodology will provide guidelines for large-scale network-wide bicycle volume estimation to the planners and engineers.

# Keywords: Bicycle, Volume, Strava, Seasonality, Factor, Short-term, Counters

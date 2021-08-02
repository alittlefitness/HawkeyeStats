# HawkeyeStats
This repo contains the Hawkeye stats for Men's and Women's cricket across Test, ODI and IPL T20 matches.  The data is a tidy version of the json data available from https://cricketapi-icc.pulselive.com/
Only matches with Hawkeye stats available are present in these datasets.

## Stats available
Ball Speed (m/s)  

PitchX & PitchY (location of impact of the ball on the pitch in metres)  

StumpsX & StumpsY (location of the ball as it passes the stumps in metres. This is calculated by Hawkeye if the batter intercepts the ball.)  

FieldX & FieldY (location on the field after the batter has played their shot.  Some matches only have scoring shot data, others have full data.)  

Notes: Matches may contain Ball Speed, Pitch & Stump location data only, Field location only or a combination of both.  Ball speed, Pitch & Stump location
data is missing for deliveries where the technology failed.

### Updates
The datasets are updated regularly, however the most recent matches may be missing.

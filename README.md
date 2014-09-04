# College Tuition and Minimum Wage Analysis

This repository contains data, sourcing notes, and analysis for the September 4, 2014 BuzzFeed article, "[These Charts Show How Much College A Minimum Wage Job Paid For, Then And Now](http://www.buzzfeed.com/gregschoofs/how-much-college-did-your-summer-job-pay-for)" by Greg Schoofs.

## Data and Sources

This repository's [`data/`](data/) folder contains three data tables:

- [`average-tuition.csv`](data/average-tuition.csv): The average in-state tuition and mandatory fees at four-year public institutions for the school years beginning in 1969 through 2011. Source: [National Center for Education Statistics](http://nces.ed.gov/programs/digest/d12/tables/dt12_381.asp)

- [`federal-minimum-wage.csv`](data/federal-minimum-wage.csv): Federal minimum wages from 1939 to the present. Source: [Department of Labor](http://www.dol.gov/whd/minwage/chart.htm)

- [`specific-schools.csv`](data/specific-schools.csv): In-state tuition and mandatory fees in 1976–77 and 2014–15 at three prominent public universities, as well as current state-level minimum wages in their respective states. Sources: [Department of Labor](http://www.dol.gov/whd/minwage/america.htm) for state-level minimum wages; see below for school-specific data sources.

*Note: Dollar figures are not adjusted for inflation*

### School-Specific Data

- __University of California, Berkeley__
    - 1976–77: $637.50, per the author's recollection and as confirmed by the university's press office.
    - 2014–15: $12,972. Source: http://admissions.berkeley.edu/costofattendance

- __University of Virginia, Charlottesville__
    - 1976–77: $734. Source: http://avillage.web.virginia.edu/iaas/instreports/studat/dd/fees.htm
    - 2014–15: $12,998. Source: Same as above

- __University of Michigan, Ann Arbor__
    - 1976–77: $941. Assumes two terms at any of the undergraduate schools or colleges. For each term, $464 in full tuition and mandatory fees, plus a "Health Service Fee" of $12.00 and a "School and College Government Fee" of $1.00. Two small additional fees — the "Michigan Student Association Fee" and "PIRGIM Fee" — were refundable upon written request. For that reason, we do not include them. Source: http://www.umich.edu/~bhlumrec/um-fees/1976_fees.pdf
    - 2014–15: Two terms at the College of Literature, Science & the Arts, undergraduate, lower division. For each term, $6,579 in tuition and $164.19 in mandatory fees. Source: http://ro.umich.edu/tuition/tuition-fees.php

## Analysis and Charts

[`notebooks/charts.ipynb`](notebooks/charts.ipynb) contains the code used to analyze the data and create the charts associated with the article. That file is an [IPython notebook](http://ipython.org/notebook.html). A rendered version of the notebook, can be viewed [viewed here](http://nbviewer.ipython.org/github/buzzfeednews/2014-09-tuition-and-minimum-wage/blob/master/notebooks/charts.ipynb).

The goal of calender is to make it easy to create ,read,write,and work with icalender(.ics,.ical or similar)files,and the scheduling data they represent ,in R.i
calender is an open standard for "exchanging calender and scheduling information between users and computers"described at 
icalender.org(the full spec can be found in a plain text file here).
Recently the UK Government endorsed the ical format in a publication for the 'open standards for Government' series.an example .ics file is provided by the .gov.uk domain,which shows holiday in England and Wales

Installation:-
install.packages("calender")
or install the cutting edge from GitHub
devtools::install_github("ATFutures/calender")
library(calender)

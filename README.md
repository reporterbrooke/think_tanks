# Foreign Government Donations to Large Think Tanks

## Description

This file contains donations from foreign government and foreign government controlled entities, such as state-owned oil companies, to 28 major U.S. think tanks between January 2011 and September 2014. The data show the existence of transactions--the fact that a donation was made--and only include amounts and other details when available. 

## Sources

Think tank annual reports, think tank websites, grant award records from Norwegian government agencies, Department of Justice records filed under the Foreign Agent Registration Act (FARA), one letter to Senate, and one email from think tank.

## Source links & Info

Norwegian grant records: https://www.oep.no/search/advancedSearch.jsp?lang=en

FARA: http://www.fara.gov/quick-search.html

Think tank annual reports: See source field in data for info on each one. Extracted in various ways depending file/html format, readability and embedded text quality. In some cases, in-stream text editor (sed), in other cases regex and/or grep. In other cases, copy and paste directly into text editor.

## Issues

1) Dates

In most cases, there is no record showing exactly when a donation was made. Also, many think tanks have different fiscal years, or use a calendar year, in their annual reports. When the source of the donation is the website, some think tanks list the time frame, while others don't. See date_info field for details on each record. 

2) Amounts

This is a database of transactions--not money donated. Most think tanks either don't provide amounts or provide a range rather than an exact amount. Also, most think tanks include "anonymous" donations on their lists, so there could be foreign government donors that are not named and not in the data. 





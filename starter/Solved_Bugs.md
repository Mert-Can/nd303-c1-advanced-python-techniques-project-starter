# Bugs and Solutions

### Requirement 1
Here we are requied to ***Find up to some number of unique NEOs on a given date or between start date and end date.***

***Solved***

solved Search requirement by creating two search instance methods in the NEOSeacher class; `equals_search` to search in a given date and `between_search` to search between start and end date.

 - `equals_search`: Here we pass as parameter the given date (string format) which is used to extract the corrresponding neo's from the NEODatabase object instantiated in the NEOSeacher. The result here is a list of NEO for that given date. 

- `between_search`: Here we pass as parameter a list containinig the start and end date (list of strings). We then split up the date string into a tuple to hole th year, month and day before creating a date object using the `datetime` library. Further more get the range of dates between the start and end dates which is used to extract the corrresponding neo's from the NEODatabase object instantiated in the NEOSeacher. The result here is a list of NEO between the start and end date. 


### Requirement 2
***Find up to some number of unique NEOs on a given date or between start date and end date larger than X kilometers.***

### Requirement 3.  
***Find up to some number of unique NEOs on a given date or between start date and end date larger than X kilometers that were hazardous.***
### Requirement 4.  
***Find up to some number of unique NEOs on a given date or between start date and end date larger than X kilometers that were hazardous and within X kilometers from Earth.***


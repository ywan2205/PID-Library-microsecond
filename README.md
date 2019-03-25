# PID-Library-microsecond
The common used arduion PID library written by br3ttb uses delay and loop to adjust the time peroid. 
This simplification satisfy the requirements of a newstarter, however, for advanced PID control design we may want the system frequency be more than kilohertz. 
To meet this requirement, we adjust the code of arduino PID library by erazing the delay code and using interrupt to adjust its operate frequency. 
This code was tested on an arduino UNO board and reaches a maximum frequency about seven kilohertz. 

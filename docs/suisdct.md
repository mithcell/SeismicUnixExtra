# SUISDCT 
Inverse sliding discrete cosine tranform 
 
## Usage 
   suisdct < stdin > stdout 
  
### Required Parameters 
| Parameter | Description                                     | Default       |
|:---------:| ----------------------------------------------- |:-------------:|
| dt=       | time sampling interval (sec)                    | trcheader     |
| nwin=     | window size of original t-f transform           |               |
 
### Optional Parameters 
| Parameter | Description                                     | Default       |
|:---------:| ----------------------------------------------- |:-------------:|
| verbose   | 0 - no advisory message, 1- for messages        |               |
 
## Notes 
This process inverts a time-frequency decomposition generated by the sliding 
discrete cosine transform (SUSDCT). 
 
## Examples 
   suvibro | susdct nwin=31 | suisdct nwin=31 | suximage 
 

# Rika-API
This repository introduces apis in api.rika.tech

## /position-record
Method: POST

Parameters:  

Name|Value|Type|Example
-|:-:|:-:|-
key|Your key|string|Rika's key
Time|Unix time stamp|int|1522926119000
pos|**Lat**,**Lng**|string|33.402126,116.435564
Type|Location type|string|**GPS** or **Network**

Return Value:  
**HTTP 200 with nothing returned** :OK  
**HTTP 400 with some or no content** :Fail

## /map

Method: GET (Need logging in)  
Parameters: *None*  
Return Value: a HTML page with a Tencent map

## /is-mili-project-concert-info-updated

Method: GET  
Parameters: *None*  
Return Value: **NO** or **Yes**  

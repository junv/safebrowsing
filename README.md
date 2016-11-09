
# safebrowsing.py - Google Safe Browsing Lookup API (v4)
#     

The safebrowsing python module is a rudimentary interface to the 
[Google Safe Browsing lookup API version 4 (v4)](https://developers.google.com/safe-browsing/v4/), for a complete implementation you may opt to use the 
[Google API Client Libraries](https://developers.google.com/api-client-library/python/apis/safebrowsing/v4).

Please feel free to contribute in improving this code.

```
import safebrowsing 
 
apikey = 'YOUR_KEY'
sb = safebrowsing.LookupAPI(apikey) 
resp = sb.threat_matches_find('ihaveaproblem.info') 
print resp 
```

Copyright (c) 2016 Jun C. Valdez - 
Code is distributed under the terms of an MIT sytle license
http://www.opensource.org/licenses/mit-license 

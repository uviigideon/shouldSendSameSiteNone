# shouldSendSameSiteNone
this php package ship with this little help function
```
\Uvii\SameSiteNone::isSafe($useragent))
```
__return__ bool to that indicate if the $useragent is safe for set cookie with SameSite=None

# Note
The code is implement by this [pseudocode post](https://www.chromium.org/updates/same-site/incompatible-clients)

Test file is reference from [linsight/should-send-same-site-none](https://github.com/linsight/should-send-same-site-none/blob/master/README.md) which is a node library to solve this problem.

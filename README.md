## WebdriverIO out-of-the-box support for LambdaTest using GeoEdge

### To run:

```sh
npm i
LT_USER_NAME="your.username" LT_ACCESS_TOKEN="your.access_token" npm run wdio
```

### What to expect?

The 2 Cucumber scenarios will run against a dummy site. 

From https://automation.lambdatest.com/test you see under the test `MetaData` > `Input Config` the following:

```json
"desiredCapabilities":{
  "geoLocation":"C2",
  "geoLocationUserCode":"AU/AL",
  "geoLocationVendor":"GeoEdge",
}
```

👏👏👏
# How to setup cloudfront signed url + s3

To be used in conjunction with this medium article.

https://medium.com/@laymanExplained/how-to-restrict-s3-content-with-aws-cloudfront-signed-urls-using-nodejs-fa4e82b64975

Referenced from https://medium.com/@apalshah/node-js-serve-private-content-using-aws-cloudfront-992e846259ae

## Getting started

1. Run `npm install` to install dependencies
2. Run `node app.js` to get signed url. Should look something like this

 https://dnl0sjq1a303m.cloudfront.net/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?Expires=1644418040349&Key-Pair-Id=APKAIB2BNQPS2D34NPJA&Signature=CPn6OgmuzHHVyzKOSLAcyL9He1lzEL2HKdlTRm4CoR2khLMjlzH8qAzyyI0pLmFfxajjZGU-9WZU3CrjvPnKURm29sojcog1v5Nc0N4N4ffB2e3aGV1d34b8BIHn7GzD7biFp0RgvR6TkbpTzZSVBMfdNAaoTzsWhfLsX367gXCuA~c70KTGZHj2zD~N99BJfe9AWDWCXqRrJB3FQuJthKPOne9A-ImT4Hvi3jfZark1xH2lZT1WlCbT3E~MNmJkhL05-R2ud5UlAMseuOgchA-0u5Vgen-jNLjDUQQ5BmptgVtMGf988qVf8IbxMt5kmFO2DsTP3Oqol-z-IyCHiA__

3. Click on link and view in browser.

<img src="https://cdn-images-1.medium.com/max/558/1*btjg3g_98YB5pPvxx1WYXA.png" alt="drawing" width="400"/>

## FYI
1. Remember to create an invalidation after each changes in cloudfront distribution configuration else updated behavior might be delayed.


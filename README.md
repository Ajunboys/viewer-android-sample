#Autodesk View and Data API workflow sample for Android


##Description

*This sample is part of the [Developer-Autodesk/Autodesk-View-and-Data-API-Samples](https://github.com/Developer-Autodesk/autodesk-view-and-data-api-samples) repository.*

This is a sample for Android devices demoing the partial workflow of using Autodesk View and Data API:

* Get token and set token
* Create bucket
* Upload model
* Start translation (registration)
* Get thumbnail of model

##Dependencies

* Make sure the necessary *.jar are available.
* Make sure to provide test models in res\raw before building the app. The package in this repository has provided a model called testmodel.nwd. These files will be copied to the storage of the mobile at <SD card root>/ADNAndroidTestView when the app is being launched. 

##Setup/Usage Instructions

* Download and install Eclipse and Android Development Tool-kit;
* Import the source code from "existing Android code into Workspaces" in Eclipse by clicking file -> Import, browse to the project folder, make sure the "project to Import" appears, and click "finish" button to import the project. 
* Get your consumer key and secret key from http://developer.autodesk.com
* Set the API keys in \src\main\Credentials.java
* Build the project to generate the *.apk
* Deploy the *.apk to a mobile device
* Open the App on android device, click [Get Token] >> token should appear in the text box below
* Input bucket name in text box under [create bucket], click [Create Bucket] >> wait for the success info
* Click [Browser Model], the files available in the storage folder will appear >> select one of them
* Click [Upload Model], wait for the success info >> the urn will appear in the text box below
* Click [Register Model] >> wait for the success info >> the text below will show the register status
* Click [show thumbnail] >> the thumbnail will appear in the image box

 
## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

##Written by 

Xiaodong Liang


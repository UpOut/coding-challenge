## UpOut Coding Challenge

Guidelines
---------------

1. The challenge has a set of features for you to choose from. Choose and build the features that you feel are important and interesting. If a feature has multiple aspects the same rules apply, you needn't complete all aspects of the feature.
2. You shouldn't spend more then 3 or 4 hours on the challenge. If you can't finish all of the challenge features within that timeframe, don't worry about it.
3. Language selection - choose the language that you feel most directly relates to the position you're applying for. For example, if you're applying for a python position, choose python.
4. You can use any 3rd party library you like.

The Challenge
---------------

Your task is to create a basic RESTful API to record and locate GPS coordinates. This API should have a subset of the following features

### Features
* Account creation and storage
* Record GPS coordinates (if account creation feature was completed, tie these to the account)
* Remove a single GPS coordinate by ID
* Remove a group of GPS coordinates by a list of IDs
* Return a subset of GPS coordinates filtered by one or more of the following:
    * A time range denoting when coordinates were added to the system
    * A set of GPS coordinates defining a bounding box
    * A set of GPS coordinates defining a polygon
    * A distance or distance range from a set point
* Delete a subset of GPS coordinates located by one or more of the following:
    * A set of GPS coordinates defining a bounding box
    * A set of GPS coordinates defining a polygon
    * A distance or distance range from a set point


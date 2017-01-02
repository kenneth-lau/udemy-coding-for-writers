# Exercise 11: Function documentation

<!-- Template (Example) -->

## `getFriendDistance(username)`
Returns the “degrees of separation” between the specified user and the current user.

Any user is some “degrees of separation” from another user. For example, if they are friends, the
distance is one, and if they are friends of friends, the distance is two. This function returns the distance
from the specified user to the current user. If there is no connection between the users, then it returns
NaN.

### Parameters:
* `username`  
Type: String  
Username of the user to get the distance from

### Returns:  
* Type: Number  
Number of degrees of separation between the users

## `safeMode(enable)`
Enables or disables safe mode

### Parameters:
* `enable`  
Type: String  
`true` to enable safe mode; `false` to disable safe mode.

### Returns:  
* No return value

## `getPremiumMode()`
Returns whether the user has paid for premium mode

### Parameters:
* No parameters

### Returns:  
* Type: Boolean  
`true` if the user has paid for premium mode; otherwise `false`.

## setTimeout(timeout)
Sets the time to wait for a response before timing out.

### Parameters:
* `timeout`  
Type: Number  
Time to wait before response times out, in seconds.

### Returns:
* No return value

## `newEvent(calendarId)`
Creates a new event for the specified calendar with the ID passed in as the parameter.

### Parameters:
* `calendarId`  
Type: Number  
ID of the calendar

### Returns:  
* Type: Number  
ID of the new event

## `getDirections(latitude, longitude, directionsCallback)`
Returns the directions from the current location to the destination location.

### Parameters:
* `latitude`  
Type: Number  
Latitude of the destination, in degrees
* `longitude`  
Type: Number  
Longitude of the destination, in degrees
* `directionsCallback`  
Type: Function  
Called when the directions come back from the server. Contains a string parameter named `directions`, which has the directions on how to get from the current location to the destination location.

## `createTransaction(amount)`
Creates a new transaction.

### Parameters:
* `amount`  
Type: Number  
Amount of the transaction, in the default currency

### Returns:
* Type: String  
ID of the new transaction

### See also:
[getTransaction](#exercise11)  
[deleteTransaction](#exercise11)






# Exercise 7: Function documentation

## `getFriendDistance(username)`
Returns the “degrees of separation” between the specified user and the current user.

Any user is some “degrees of separation” from another user. For example, if they are friends, the distance is one, and if they are friends of friends, the distance is two. This function returns the distance from the specified user to the current user. If there is no connection between the users, then it returns NaN.

### Parameters:
* `username`  
    Type: String  
    Username of the user to get the distance from

### Returns:
* Type: Number  
Number of degrees of separation between the users

## `logout()`
Logs out the current user.

## `getNumberFriends()`
Gets the number of friends the current user has.

### Returns:
* Type: Numbers  
Number of friends the current user has

## `requestFriend(username)`
Sends a friend request to a user.

### Paramters:
* `username`  
Type: String  
Username of the user to send request to

## `post(statusUpdate)`
Posts a status update.

The status update can be up to 1000 characters long. Returns true if the post succeeded and false if the post fails. 

### Parameters:
* `statusUpdate`  
Type: String
Status update message.

### Returns:
* Type: Number  
True if the post succeeds; false if the post fails.

## `like(postId, likeType)`
Likes a post.

Returns whether the post succeeded.

### Parameters
* `postId`  
Type: Integer  
ID of the post

* `likeType`  
Type: String  
The type of like. Valid values: "Like", "Love", or "Empathy"

### Returns
* Type: Number  
True if the post succeeds; false if the post fails.
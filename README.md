#Wish I Was Here - Remote XML Resources

Remote XML resources, for use with the [Wish I Was Here](https://github.com/wishiwashere/TeamProject-2016) Android application, as part of the Team Project module of the Creative Multimedia B.Sc (Hons) degree course in Limerick Institute of Technology, Clonmel, Co. Tipperary.

###Personal Portfolios
_Eiren McLoughlin_: [eiren.projects.ie](www.eiren.projects.ie)  
_Laura Pigott_: [pigottlaura.com](www.pigottlaura.com)

###XML Resources
* [User Preferences](https://github.com/wishiwashere/wishiwashere.github.io/blob/master/user_preferences.xml)
	* This file will be loaded from the app if a user does not already have preferences saved to their device (i.e. the first time they use the app)
	* The data in this file is then used to generate the default preferences for this user, and will be the template for their locally stored preferences on their device
* [Random Locations](https://github.com/wishiwashere/wishiwashere.github.io/blob/master/random_locations.xml)
	* This file will be loaded each time the user opens the app
	* The data in this file will be used to initalise the array of random locations available to the user during that app session
	* By storing this data remotely, we can update the random locations for all apps, without having to create a new release for the app.
	* Random locations are stored in a separate XML file to the user preferences, so that even if a user deletes all of their favourite locations, there will still be random locations available to them.
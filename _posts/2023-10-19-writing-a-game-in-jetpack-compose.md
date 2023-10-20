## Writing a Game In Jetpack Compose

####  Skills
- Android
	* RoomDB
	* Jetpack Compose
	* Kotlin Coroutines
	* Dagger Hilt Dependency Injection
	* Clean Architecture
	* MVVM
  

### Preface
I've been developing Android apps for my job for approximately 6 years now. I thought it was about time I start working on taking all the learning from the thousands of mistakes I've made and get something on the Google Play Store that I could be proud of. I decided (since I'm bad at art) to make a text-based business simulation game. I don't have any of the typical Calculator and Notes apps that everyone who's ever learned app development has made before on my Github, and instead I put my effort into this.

## Architecture

Even though I've created my fair share of spaghetti in the past, I wanted to create a project where the structure of the application followed Clean principles and I thought this was a great reason to create something along those lines since I had plans of releasing this publically. The app's data follows these Clean principles in separate layers of concern and also follows the recommended Android MVVM architecture while using Jetpack Compose for all aspects of the UI. 

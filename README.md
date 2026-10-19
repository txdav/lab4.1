Campground Explorer

Overview

Campground Explorer is an Android application developed for CodePath's AND102 Intermediate Android Development course. The app uses the National Park Service API to retrieve campground information and display it in an interactive list.

Users can select a campground to view its name, description, location, and image on a dedicated details screen.

Features

Retrieves campground data from the National Park Service API.

Displays campgrounds in a scrollable RecyclerView.

Shows campground names, descriptions, locations, and images.

Opens a details screen when a campground is selected.

Includes a back button to return to the campground list.

Loads images using Glide.

Demo

Demo GIF: The demo GIF was created, but it would not upload correctly to the repository. Therefore, the GIF is not currently displayed in this README.

Technologies Used named Lab 4.1 gif

Kotlin

Android Studio

Android SDK

RecyclerView

National Park Service API

AsyncHttpClient

Kotlin Serialization

Glide

Git and GitHub

Setup Instructions

Clone this repository.

Open the project in Android Studio.

Configure your National Park Service API key in the local apikey.properties file using the format expected by the project.

Sync the Gradle project.

Run the application using an Android emulator or compatible Android device.

Note: Do not commit or publicly share your API key.

What I Learned

Making API requests and retrieving external data.

Parsing JSON responses into Kotlin data classes.

Displaying API data using RecyclerView and a custom adapter.

Passing selected campground information between activities.

Loading images with Glide.

Building and testing a multi-screen Android application.

Author

Taylor Davis
](https://github.com/txdav/lab4.1.git)](https://github.com/txdav/lab4.1.git)

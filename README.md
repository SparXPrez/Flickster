# Project 2 - *Flickster*

**Flickster** shows the latest movies currently playing in theaters. The app utilizes the Movie Database API to display images and basic information about these movies to the user.

Time spent: **3** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

* [X] Views should be responsive for both landscape/portrait mode.
      * [X] In portrait mode, the poster image, title, and movie overview is shown.
      * [X] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

The following **optional** features are implemented:

* [ ] Display a nice default [placeholder graphic](https://guides.codepath.com/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
* [ ] Improved the user interface by experimenting with styling and coloring.
* [ ] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/SparXPrez/Flickster/blob/master/Flickster.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

- I had an issue with getting the varialbe "rvMovies" to show up in MovieActivity file. However, the fix was adding it into the manifest file

-I had issues trying to get the app to rotate in landscape mode, however I found that it was because I had my emulator's screen lock to portrait mode.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2019] [Stephan Duroseau]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

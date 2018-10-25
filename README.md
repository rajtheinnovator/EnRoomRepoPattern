# EnRoomRepoPattern
A simple app that demonstrates accessing Room database DAO and works with LiveData. Also, makes use of repository pattern

#### Source of hardcoded data used is: https://gist.github.com/rajtheinnovator/a45ac7e2c1ec92c4aabc72891fbf84cf as mentioned here: https://github.com/enpassio/EnDataSource/blob/master/README.md

# Android Architecture Components(Room) sample

You can use the samples in this project as a learning reference, or as a starting point for creating your own apps. The focus of this project is on demonstrating how to structure your code, design your architecture, and the eventual impact of adopting these patterns on testing and maintaining your app. You can use the techniques demonstrated here in many different ways to build apps. Your own particular priorities will impact how you implement the concepts in these projects, so you should not consider these samples to be canonical examples. To ensure the focus is kept on the aims described above, the app uses a simple UI.

## Explore the samples

This project hosts each sample app in separate repository branches. For more information, see the `README.md` file in each branch.


### Samples in progress

| Sample | Description |
| ------------- | ------------- |
| [dev-room-news](https://github.com/enpassio/EnRoomRepoPattern/tree/dev-room-news) | Based on the todo-rxjava sample, this version incorporates the [Model‑View‑ViewModel](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel) pattern.|

For information about planned samples, see ["New sample" issues](https://github.com/enpassio/EnRoomRepoPattern/issues?q=is%3Aissue+is%3Aopen+label%3A%22New+sample%22).


## Choose a sample for your app

Each sample includes a dedicated `README.md` file where you can find related metrics, as well as subjective assessments and observations by contributors. The following factors are worth considering when selecting a particular sample for your app:

* The size of the app you are developing
* The size and experience of your team
* The amount of maintenance that you are expecting to have to do
* Whether you need a tablet layout
* Whether you need to support multiple platforms
* Your preference for the compactness of your codebase


## Open a sample in Android Studio

To open one of the samples in Android Studio, begin by checking out one of the sample branches, and then open the `room/` directory in Android Studio. The following series of steps illustrate how to open the [room-news](https://github.com/enpassio/EnRoomRepoPattern/tree/room-news) sample.

**Note:** The master branch does not compile.

Clone the repository:

```
git clone git@github.com:enpassio/EnRoomRepoPattern.git
```

Checkout the room-news sample:
```
git checkout room-news
```

**Note:** To review a different sample, replace `room-news` with the name of sample you want to check out.

Finally open the `room/` directory in Android Studio.

## Contributors

This project is **built by the community**, and curated by Enpassio as well as other maintainers.

### Team Enpassio

[Abhishek Raj](https://github.com/rajtheinnovator) - Core developer



For more information on joining the project, see [how to become a contributor](https://github.com/enpassio/EnRoomRepoPattern/blob/master/CONTRIBUTING.md).

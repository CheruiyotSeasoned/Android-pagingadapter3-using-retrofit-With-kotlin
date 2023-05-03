# Android-pagingadapter3-using-retrofit-With-kotlin

# PAGING ADAPTER 3
##android app with kotlin - feel freeto reuse


Android Paging 
The Paging library helps you load and display pages of data or small chunks of data at a time from a larger dataset from local storage or over network. Loading partial data on demand reduces usage of network bandwidth and system resources.

 It integrates cleanly with other Jetpack components, and provide first-class Kotlin support.
###3importance of paging 3
#####Benefits of using the Paging library
The Paging library includes the following features:
- Provides in-memory caching of the paged data that assures the systematic use of device resources.
- Prevents duplication of the API request, ensuring that your app uses network bandwidth and system resources efficiently.
- Configurable RecyclerView adapters that automatically request data as the user scrolls toward the end of the loaded data.
- Finest support for Kotlin coroutines and Flow, as well as LiveData and RxJava.
- Built-in functionality to add loading state headers, footers, and list separators.
- Built-in support for error handling, including refresh and retry capabilities.
- ✨Magic ✨

#### Features
Paging Library Components
 To implement “infinite scroll” functionality , we will use the following Paging library components:
- PagingData :  A container for paginated data. It connects the ViewModel layer to the UI. 
- PagingSource : PagingSource object defines a source of data and how to retrieve data from that source. A PagingSource object can load data from any single source, including network sources and local databases.
- Pager.flow : builds a Flow<PagingData>.
- PagingDataAdapter : a RecyclerView.Adapter that presents PagingData in a RecyclerView. 


## Tech

Dillinger uses a number of open source projects to work properly:

- [Gradle] - android app builder
- [Android studio Editor] - awesome web-based jetbrains editor
- [Kotlin] - great Lightwaeight programming language






 

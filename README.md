# PersistentLoadingCache
The PersistentLoadingCache library is an internal implementation of a hard drive-backed loading cache in Java. 

This library is based on Google's Guava LoadingCache implementation, and adds flexible support for persistence strategies to carry cached data over between program invocations. 

This released currently includes a simple filesystem-based persistence strategy, which stores persisted and extended cached data to the local filesystem at a specified folder location. Custom persistence strategies may be implemented and used in PersistentLoadingCaches as desired. 

# NOTE:
This library is in early alpha, and is not ready for production deployment at this time.

# License
Open-source under the Apache 2.0 license

# DefaultAPI

All URIs are relative to *https://rickandmortyapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**apiEpisodeGet**](DefaultAPI.md#apiepisodeget) | **GET** /api/episode/ | 


# **apiEpisodeGet**
```swift
    open class func apiEpisodeGet(completion: @escaping (_ data: ResultList?, _ error: Error?) -> Void)
```



### Example 
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import RickAndMortyApiClient


DefaultAPI.apiEpisodeGet() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**ResultList**](ResultList.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \MonitorManagementAPI

All URIs are relative to *http://api.upbot.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteASpecificMonitor**](MonitorManagementAPI.md#DeleteASpecificMonitor) | **Delete** /api/monitors/{id} | Delete a specific monitor.
[**DisplayAListingOfTheResource**](MonitorManagementAPI.md#DisplayAListingOfTheResource) | **Get** /api/monitors | Display a listing of the resource.
[**StoreANewlyCreatedResourceInStorage**](MonitorManagementAPI.md#StoreANewlyCreatedResourceInStorage) | **Post** /api/monitors | Store a newly created resource in storage.



## DeleteASpecificMonitor

> string DeleteASpecificMonitor(ctx, id).Execute()

Delete a specific monitor.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/upbothq/upbot-go-sdk"
)

func main() {
	id := "0199d5d6-c417-71a2-9aa1-576f812c24b7" // string | The ID of the monitor.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MonitorManagementAPI.DeleteASpecificMonitor(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorManagementAPI.DeleteASpecificMonitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteASpecificMonitor`: string
	fmt.Fprintf(os.Stdout, "Response from `MonitorManagementAPI.DeleteASpecificMonitor`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the monitor. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteASpecificMonitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisplayAListingOfTheResource

> DisplayAListingOfTheResource200Response DisplayAListingOfTheResource(ctx).Execute()

Display a listing of the resource.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/upbothq/upbot-go-sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MonitorManagementAPI.DisplayAListingOfTheResource(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorManagementAPI.DisplayAListingOfTheResource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisplayAListingOfTheResource`: DisplayAListingOfTheResource200Response
	fmt.Fprintf(os.Stdout, "Response from `MonitorManagementAPI.DisplayAListingOfTheResource`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDisplayAListingOfTheResourceRequest struct via the builder pattern


### Return type

[**DisplayAListingOfTheResource200Response**](DisplayAListingOfTheResource200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StoreANewlyCreatedResourceInStorage

> StoreANewlyCreatedResourceInStorage201Response StoreANewlyCreatedResourceInStorage(ctx).StoreANewlyCreatedResourceInStorageRequest(storeANewlyCreatedResourceInStorageRequest).Execute()

Store a newly created resource in storage.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/upbothq/upbot-go-sdk"
)

func main() {
	storeANewlyCreatedResourceInStorageRequest := *openapiclient.NewStoreANewlyCreatedResourceInStorageRequest("Type_example") // StoreANewlyCreatedResourceInStorageRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MonitorManagementAPI.StoreANewlyCreatedResourceInStorage(context.Background()).StoreANewlyCreatedResourceInStorageRequest(storeANewlyCreatedResourceInStorageRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorManagementAPI.StoreANewlyCreatedResourceInStorage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StoreANewlyCreatedResourceInStorage`: StoreANewlyCreatedResourceInStorage201Response
	fmt.Fprintf(os.Stdout, "Response from `MonitorManagementAPI.StoreANewlyCreatedResourceInStorage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStoreANewlyCreatedResourceInStorageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeANewlyCreatedResourceInStorageRequest** | [**StoreANewlyCreatedResourceInStorageRequest**](StoreANewlyCreatedResourceInStorageRequest.md) |  | 

### Return type

[**StoreANewlyCreatedResourceInStorage201Response**](StoreANewlyCreatedResourceInStorage201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


# \RecordsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RecordsDelete**](RecordsAPI.md#RecordsDelete) | **Delete** /records | Deletes the dns records.
[**RecordsGet**](RecordsAPI.md#RecordsGet) | **Get** /records | Retrieves all records.
[**RecordsPost**](RecordsAPI.md#RecordsPost) | **Post** /records | Add records.
[**RecordsRecordIdDelete**](RecordsAPI.md#RecordsRecordIdDelete) | **Delete** /records/{record_id} | Deletes the dns record.
[**RecordsRecordIdGet**](RecordsAPI.md#RecordsRecordIdGet) | **Get** /records/{record_id} | Get DNS record.



## RecordsDelete

> RecordCollectionOutput RecordsDelete(ctx).RequestBody(requestBody).Execute()

Deletes the dns records.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kvalitetsit/medcom-sdn-dns-api-client-go"
)

func main() {
	requestBody := []string{"Property_example"} // []string | The new records.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.RecordsDelete(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.RecordsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordsDelete`: RecordCollectionOutput
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.RecordsDelete`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRecordsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **[]string** | The new records. | 

### Return type

[**RecordCollectionOutput**](RecordCollectionOutput.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordsGet

> RecordCollectionOutput RecordsGet(ctx).Fqdn(fqdn).Offset(offset).Limit(limit).Type_(type_).Source(source).Execute()

Retrieves all records.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kvalitetsit/medcom-sdn-dns-api-client-go"
)

func main() {
	fqdn := "fqdn_example" // string | Fully qualifies domain name (optional)
	offset := int32(0) // int32 | Number of items to skip (optional) (default to 0)
	limit := int32(20) // int32 |  (optional)
	type_ := openapiclient.DnsRecordType("A") // DnsRecordType |  (optional)
	source := "source_example" // string | The source of the record (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.RecordsGet(context.Background()).Fqdn(fqdn).Offset(offset).Limit(limit).Type_(type_).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.RecordsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordsGet`: RecordCollectionOutput
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.RecordsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRecordsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fqdn** | **string** | Fully qualifies domain name | 
 **offset** | **int32** | Number of items to skip | [default to 0]
 **limit** | **int32** |  | 
 **type_** | [**DnsRecordType**](DnsRecordType.md) |  | 
 **source** | **string** | The source of the record | 

### Return type

[**RecordCollectionOutput**](RecordCollectionOutput.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordsPost

> RecordCollectionOutput RecordsPost(ctx).RecordCollectionInput(recordCollectionInput).Execute()

Add records.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kvalitetsit/medcom-sdn-dns-api-client-go"
)

func main() {
	recordCollectionInput := *openapiclient.NewRecordCollectionInput([]openapiclient.RecordInput{openapiclient.RecordInput{AAAARecord: openapiclient.NewAAAARecord("dsdn.dk", "Type_example", "Source_example", "2001:db8::10")}}) // RecordCollectionInput | The new records.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.RecordsPost(context.Background()).RecordCollectionInput(recordCollectionInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.RecordsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordsPost`: RecordCollectionOutput
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.RecordsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRecordsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **recordCollectionInput** | [**RecordCollectionInput**](RecordCollectionInput.md) | The new records. | 

### Return type

[**RecordCollectionOutput**](RecordCollectionOutput.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordsRecordIdDelete

> RecordOutput RecordsRecordIdDelete(ctx, recordId).Execute()

Deletes the dns record.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kvalitetsit/medcom-sdn-dns-api-client-go"
)

func main() {
	recordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Fully qualifies domain name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.RecordsRecordIdDelete(context.Background(), recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.RecordsRecordIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordsRecordIdDelete`: RecordOutput
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.RecordsRecordIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**recordId** | **string** | Fully qualifies domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiRecordsRecordIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RecordOutput**](RecordOutput.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecordsRecordIdGet

> RecordOutput RecordsRecordIdGet(ctx, recordId).Execute()

Get DNS record.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kvalitetsit/medcom-sdn-dns-api-client-go"
)

func main() {
	recordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | the UUID of the record

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.RecordsRecordIdGet(context.Background(), recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.RecordsRecordIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecordsRecordIdGet`: RecordOutput
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.RecordsRecordIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**recordId** | **string** | the UUID of the record | 

### Other Parameters

Other parameters are passed through a pointer to a apiRecordsRecordIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RecordOutput**](RecordOutput.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


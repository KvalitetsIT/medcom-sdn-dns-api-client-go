# \RecordsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DomainsDomainIdRecordsGet**](RecordsAPI.md#DomainsDomainIdRecordsGet) | **Get** /domains/{domain_id}/records | Retrieves all records within the given domain.
[**DomainsDomainIdRecordsPost**](RecordsAPI.md#DomainsDomainIdRecordsPost) | **Post** /domains/{domain_id}/records | Add record to domain.
[**DomainsDomainIdRecordsRecordIdDelete**](RecordsAPI.md#DomainsDomainIdRecordsRecordIdDelete) | **Delete** /domains/{domain_id}/records/{record_id} | Deletes the dns record with the fully qualified domain name.
[**DomainsDomainIdRecordsRecordIdGet**](RecordsAPI.md#DomainsDomainIdRecordsRecordIdGet) | **Get** /domains/{domain_id}/records/{record_id} | Get DNS record with the fully qualified domain name.



## DomainsDomainIdRecordsGet

> RecordCollection DomainsDomainIdRecordsGet(ctx, domainId).Fqdn(fqdn).Offset(offset).Limit(limit).Type_(type_).Execute()

Retrieves all records within the given domain.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Fully qualifies domain name
	fqdn := "fqdn_example" // string | Fully qualifies domain name (optional)
	offset := int32(0) // int32 | Number of items to skip (optional) (default to 0)
	limit := int32(20) // int32 |  (optional) (default to 20)
	type_ := openapiclient.DnsRecordType("A") // DnsRecordType |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.DomainsDomainIdRecordsGet(context.Background(), domainId).Fqdn(fqdn).Offset(offset).Limit(limit).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.DomainsDomainIdRecordsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdRecordsGet`: RecordCollection
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.DomainsDomainIdRecordsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Fully qualifies domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdRecordsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **fqdn** | **string** | Fully qualifies domain name | 
 **offset** | **int32** | Number of items to skip | [default to 0]
 **limit** | **int32** |  | [default to 20]
 **type_** | [**DnsRecordType**](DnsRecordType.md) |  | 

### Return type

[**RecordCollection**](RecordCollection.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsDomainIdRecordsPost

> RecordCollection DomainsDomainIdRecordsPost(ctx, domainId).RecordCollection(recordCollection).Execute()

Add record to domain.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | the UUID of the domain
	recordCollection := *openapiclient.NewRecordCollection([]openapiclient.Record{openapiclient.Record{AAAARecord: openapiclient.NewAAAARecord("example.com.", "2001:db8::10")}}) // RecordCollection | The new organisation.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.DomainsDomainIdRecordsPost(context.Background(), domainId).RecordCollection(recordCollection).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.DomainsDomainIdRecordsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdRecordsPost`: RecordCollection
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.DomainsDomainIdRecordsPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | the UUID of the domain | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdRecordsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **recordCollection** | [**RecordCollection**](RecordCollection.md) | The new organisation. | 

### Return type

[**RecordCollection**](RecordCollection.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsDomainIdRecordsRecordIdDelete

> Record DomainsDomainIdRecordsRecordIdDelete(ctx, domainId, recordId).Execute()

Deletes the dns record with the fully qualified domain name.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Fully qualifies domain name
	recordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Fully qualifies domain name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.DomainsDomainIdRecordsRecordIdDelete(context.Background(), domainId, recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.DomainsDomainIdRecordsRecordIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdRecordsRecordIdDelete`: Record
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.DomainsDomainIdRecordsRecordIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | Fully qualifies domain name | 
**recordId** | **string** | Fully qualifies domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdRecordsRecordIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Record**](Record.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsDomainIdRecordsRecordIdGet

> Record DomainsDomainIdRecordsRecordIdGet(ctx, domainId, recordId).Execute()

Get DNS record with the fully qualified domain name.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | the UUID of the domain
	recordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | the UUID of the record

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecordsAPI.DomainsDomainIdRecordsRecordIdGet(context.Background(), domainId, recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecordsAPI.DomainsDomainIdRecordsRecordIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdRecordsRecordIdGet`: Record
	fmt.Fprintf(os.Stdout, "Response from `RecordsAPI.DomainsDomainIdRecordsRecordIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | the UUID of the domain | 
**recordId** | **string** | the UUID of the record | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdRecordsRecordIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Record**](Record.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


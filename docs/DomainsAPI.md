# \DomainsAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DomainsDomainIdDelete**](DomainsAPI.md#DomainsDomainIdDelete) | **Delete** /domains/{domain_id} | Deletes the domain and all associated records.
[**DomainsDomainIdGet**](DomainsAPI.md#DomainsDomainIdGet) | **Get** /domains/{domain_id} | Gets the domain associated with the specified UUID.
[**DomainsGet**](DomainsAPI.md#DomainsGet) | **Get** /domains | Get all DNS records
[**DomainsPost**](DomainsAPI.md#DomainsPost) | **Post** /domains | Add domain.



## DomainsDomainIdDelete

> Domain DomainsDomainIdDelete(ctx, domainId).Execute()

Deletes the domain and all associated records.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The UUID of the domain

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsDomainIdDelete(context.Background(), domainId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsDomainIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdDelete`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsDomainIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | The UUID of the domain | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Domain**](Domain.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsDomainIdGet

> Domain DomainsDomainIdGet(ctx, domainId).Execute()

Gets the domain associated with the specified UUID.



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
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The UUID of the domain

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsDomainIdGet(context.Background(), domainId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsDomainIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsDomainIdGet`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsDomainIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domainId** | **string** | The UUID of the domain | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsDomainIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Domain**](Domain.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsGet

> []Domain DomainsGet(ctx).Offset(offset).Limit(limit).Execute()

Get all DNS records



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
	offset := int32(0) // int32 | Number of items to skip (optional) (default to 0)
	limit := int32(20) // int32 | Number of items to return (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsGet(context.Background()).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsGet`: []Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** | Number of items to skip | [default to 0]
 **limit** | **int32** | Number of items to return | [default to 20]

### Return type

[**[]Domain**](Domain.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsPost

> Domain DomainsPost(ctx).Domain(domain).Execute()

Add domain.



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
	domain := *openapiclient.NewDomain("mail.portal") // Domain | The new domain.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainsAPI.DomainsPost(context.Background()).Domain(domain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainsAPI.DomainsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsPost`: Domain
	fmt.Fprintf(os.Stdout, "Response from `DomainsAPI.DomainsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domain** | [**Domain**](Domain.md) | The new domain. | 

### Return type

[**Domain**](Domain.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


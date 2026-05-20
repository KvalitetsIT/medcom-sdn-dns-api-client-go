# NSRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Nameserver** | **string** | Authoritative nameserver hostname. | 

## Methods

### NewNSRecord

`func NewNSRecord(nameserver string, ) *NSRecord`

NewNSRecord instantiates a new NSRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNSRecordWithDefaults

`func NewNSRecordWithDefaults() *NSRecord`

NewNSRecordWithDefaults instantiates a new NSRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNameserver

`func (o *NSRecord) GetNameserver() string`

GetNameserver returns the Nameserver field if non-nil, zero value otherwise.

### GetNameserverOk

`func (o *NSRecord) GetNameserverOk() (*string, bool)`

GetNameserverOk returns a tuple with the Nameserver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameserver

`func (o *NSRecord) SetNameserver(v string)`

SetNameserver sets Nameserver field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



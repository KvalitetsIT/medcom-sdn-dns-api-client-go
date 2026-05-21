# CNAMERecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | Pointer to **string** | Alias hostname | [optional] 
**CanonicalName** | **string** | Canonical hostname target. | 

## Methods

### NewCNAMERecord

`func NewCNAMERecord(canonicalName string, ) *CNAMERecord`

NewCNAMERecord instantiates a new CNAMERecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCNAMERecordWithDefaults

`func NewCNAMERecordWithDefaults() *CNAMERecord`

NewCNAMERecordWithDefaults instantiates a new CNAMERecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *CNAMERecord) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *CNAMERecord) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *CNAMERecord) SetHost(v string)`

SetHost sets Host field to given value.

### HasHost

`func (o *CNAMERecord) HasHost() bool`

HasHost returns a boolean if a field has been set.

### GetCanonicalName

`func (o *CNAMERecord) GetCanonicalName() string`

GetCanonicalName returns the CanonicalName field if non-nil, zero value otherwise.

### GetCanonicalNameOk

`func (o *CNAMERecord) GetCanonicalNameOk() (*string, bool)`

GetCanonicalNameOk returns a tuple with the CanonicalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalName

`func (o *CNAMERecord) SetCanonicalName(v string)`

SetCanonicalName sets CanonicalName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CNAMERecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Ttl** | Pointer to **int32** | DNS Time To Live in seconds. | [optional] 
**Type** | **string** | DNS record type discriminator. | 
**Host** | **string** | Alias hostname | 
**CanonicalName** | **string** | Canonical hostname target. | 

## Methods

### NewCNAMERecord

`func NewCNAMERecord(type_ string, host string, canonicalName string, ) *CNAMERecord`

NewCNAMERecord instantiates a new CNAMERecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCNAMERecordWithDefaults

`func NewCNAMERecordWithDefaults() *CNAMERecord`

NewCNAMERecordWithDefaults instantiates a new CNAMERecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CNAMERecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CNAMERecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CNAMERecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CNAMERecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTtl

`func (o *CNAMERecord) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *CNAMERecord) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *CNAMERecord) SetTtl(v int32)`

SetTtl sets Ttl field to given value.

### HasTtl

`func (o *CNAMERecord) HasTtl() bool`

HasTtl returns a boolean if a field has been set.

### GetType

`func (o *CNAMERecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CNAMERecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CNAMERecord) SetType(v string)`

SetType sets Type field to given value.


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



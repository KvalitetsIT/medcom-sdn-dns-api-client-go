# MXRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Ttl** | Pointer to **int32** | DNS Time To Live in seconds. | [optional] 
**Type** | **string** | DNS record type discriminator. | 
**Priority** | **int32** | Mail server priority where lower values are preferred. | 
**Exchange** | **string** | Mail server hostname. | 

## Methods

### NewMXRecord

`func NewMXRecord(type_ string, priority int32, exchange string, ) *MXRecord`

NewMXRecord instantiates a new MXRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMXRecordWithDefaults

`func NewMXRecordWithDefaults() *MXRecord`

NewMXRecordWithDefaults instantiates a new MXRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MXRecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MXRecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MXRecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *MXRecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTtl

`func (o *MXRecord) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *MXRecord) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *MXRecord) SetTtl(v int32)`

SetTtl sets Ttl field to given value.

### HasTtl

`func (o *MXRecord) HasTtl() bool`

HasTtl returns a boolean if a field has been set.

### GetType

`func (o *MXRecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MXRecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MXRecord) SetType(v string)`

SetType sets Type field to given value.


### GetPriority

`func (o *MXRecord) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *MXRecord) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *MXRecord) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetExchange

`func (o *MXRecord) GetExchange() string`

GetExchange returns the Exchange field if non-nil, zero value otherwise.

### GetExchangeOk

`func (o *MXRecord) GetExchangeOk() (*string, bool)`

GetExchangeOk returns a tuple with the Exchange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchange

`func (o *MXRecord) SetExchange(v string)`

SetExchange sets Exchange field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# MXRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Priority** | **int32** | Mail server priority where lower values are preferred. | 
**Exchange** | **string** | Mail server hostname. | 

## Methods

### NewMXRecord

`func NewMXRecord(priority int32, exchange string, ) *MXRecord`

NewMXRecord instantiates a new MXRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMXRecordWithDefaults

`func NewMXRecordWithDefaults() *MXRecord`

NewMXRecordWithDefaults instantiates a new MXRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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



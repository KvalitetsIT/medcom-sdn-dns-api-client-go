# CAARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Flags** | **int32** | Flags controlling record interpretation. | 
**Tag** | **string** | CAA property tag defining the authorization behavior. | 
**Value** | **string** | Certificate authority authorization value. | 

## Methods

### NewCAARecord

`func NewCAARecord(flags int32, tag string, value string, ) *CAARecord`

NewCAARecord instantiates a new CAARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCAARecordWithDefaults

`func NewCAARecordWithDefaults() *CAARecord`

NewCAARecordWithDefaults instantiates a new CAARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFlags

`func (o *CAARecord) GetFlags() int32`

GetFlags returns the Flags field if non-nil, zero value otherwise.

### GetFlagsOk

`func (o *CAARecord) GetFlagsOk() (*int32, bool)`

GetFlagsOk returns a tuple with the Flags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlags

`func (o *CAARecord) SetFlags(v int32)`

SetFlags sets Flags field to given value.


### GetTag

`func (o *CAARecord) GetTag() string`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *CAARecord) GetTagOk() (*string, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *CAARecord) SetTag(v string)`

SetTag sets Tag field to given value.


### GetValue

`func (o *CAARecord) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CAARecord) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CAARecord) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



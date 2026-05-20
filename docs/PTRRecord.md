# PTRRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pointer** | **string** | Reverse DNS hostname target. | 

## Methods

### NewPTRRecord

`func NewPTRRecord(pointer string, ) *PTRRecord`

NewPTRRecord instantiates a new PTRRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPTRRecordWithDefaults

`func NewPTRRecordWithDefaults() *PTRRecord`

NewPTRRecordWithDefaults instantiates a new PTRRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPointer

`func (o *PTRRecord) GetPointer() string`

GetPointer returns the Pointer field if non-nil, zero value otherwise.

### GetPointerOk

`func (o *PTRRecord) GetPointerOk() (*string, bool)`

GetPointerOk returns a tuple with the Pointer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPointer

`func (o *PTRRecord) SetPointer(v string)`

SetPointer sets Pointer field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



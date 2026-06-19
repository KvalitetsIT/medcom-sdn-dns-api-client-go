# CAARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Ttl** | Pointer to **int32** | DNS Time To Live in seconds. | [optional] 
**Type** | **string** | DNS record type discriminator. | 
**Name** | **string** | key/name. | 
**Flags** | **int32** | Flags controlling record interpretation. | 
**Tag** | **string** | CAA property tag defining the authorization behavior. | 
**Value** | **string** | Certificate authority authorization value. | 

## Methods

### NewCAARecord

`func NewCAARecord(type_ string, name string, flags int32, tag string, value string, ) *CAARecord`

NewCAARecord instantiates a new CAARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCAARecordWithDefaults

`func NewCAARecordWithDefaults() *CAARecord`

NewCAARecordWithDefaults instantiates a new CAARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CAARecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CAARecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CAARecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CAARecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTtl

`func (o *CAARecord) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *CAARecord) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *CAARecord) SetTtl(v int32)`

SetTtl sets Ttl field to given value.

### HasTtl

`func (o *CAARecord) HasTtl() bool`

HasTtl returns a boolean if a field has been set.

### GetType

`func (o *CAARecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CAARecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CAARecord) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *CAARecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CAARecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CAARecord) SetName(v string)`

SetName sets Name field to given value.


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



# SOARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Ttl** | Pointer to **int32** | DNS Time To Live in seconds. | [optional] 
**Type** | **string** | DNS record type discriminator. | 
**MName** | **string** | Primary master nameserver for the zone. | 
**RName** | **string** | Responsible party email (encoded format). | 
**Serial** | **int32** |  | 
**Refresh** | **int32** |  | 
**Retry** | **int32** |  | 
**Expire** | **int32** |  | 
**Minimum** | **int32** |  | 

## Methods

### NewSOARecord

`func NewSOARecord(type_ string, mName string, rName string, serial int32, refresh int32, retry int32, expire int32, minimum int32, ) *SOARecord`

NewSOARecord instantiates a new SOARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSOARecordWithDefaults

`func NewSOARecordWithDefaults() *SOARecord`

NewSOARecordWithDefaults instantiates a new SOARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SOARecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SOARecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SOARecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SOARecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTtl

`func (o *SOARecord) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *SOARecord) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *SOARecord) SetTtl(v int32)`

SetTtl sets Ttl field to given value.

### HasTtl

`func (o *SOARecord) HasTtl() bool`

HasTtl returns a boolean if a field has been set.

### GetType

`func (o *SOARecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SOARecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SOARecord) SetType(v string)`

SetType sets Type field to given value.


### GetMName

`func (o *SOARecord) GetMName() string`

GetMName returns the MName field if non-nil, zero value otherwise.

### GetMNameOk

`func (o *SOARecord) GetMNameOk() (*string, bool)`

GetMNameOk returns a tuple with the MName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMName

`func (o *SOARecord) SetMName(v string)`

SetMName sets MName field to given value.


### GetRName

`func (o *SOARecord) GetRName() string`

GetRName returns the RName field if non-nil, zero value otherwise.

### GetRNameOk

`func (o *SOARecord) GetRNameOk() (*string, bool)`

GetRNameOk returns a tuple with the RName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRName

`func (o *SOARecord) SetRName(v string)`

SetRName sets RName field to given value.


### GetSerial

`func (o *SOARecord) GetSerial() int32`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *SOARecord) GetSerialOk() (*int32, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *SOARecord) SetSerial(v int32)`

SetSerial sets Serial field to given value.


### GetRefresh

`func (o *SOARecord) GetRefresh() int32`

GetRefresh returns the Refresh field if non-nil, zero value otherwise.

### GetRefreshOk

`func (o *SOARecord) GetRefreshOk() (*int32, bool)`

GetRefreshOk returns a tuple with the Refresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefresh

`func (o *SOARecord) SetRefresh(v int32)`

SetRefresh sets Refresh field to given value.


### GetRetry

`func (o *SOARecord) GetRetry() int32`

GetRetry returns the Retry field if non-nil, zero value otherwise.

### GetRetryOk

`func (o *SOARecord) GetRetryOk() (*int32, bool)`

GetRetryOk returns a tuple with the Retry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetry

`func (o *SOARecord) SetRetry(v int32)`

SetRetry sets Retry field to given value.


### GetExpire

`func (o *SOARecord) GetExpire() int32`

GetExpire returns the Expire field if non-nil, zero value otherwise.

### GetExpireOk

`func (o *SOARecord) GetExpireOk() (*int32, bool)`

GetExpireOk returns a tuple with the Expire field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpire

`func (o *SOARecord) SetExpire(v int32)`

SetExpire sets Expire field to given value.


### GetMinimum

`func (o *SOARecord) GetMinimum() int32`

GetMinimum returns the Minimum field if non-nil, zero value otherwise.

### GetMinimumOk

`func (o *SOARecord) GetMinimumOk() (*int32, bool)`

GetMinimumOk returns a tuple with the Minimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimum

`func (o *SOARecord) SetMinimum(v int32)`

SetMinimum sets Minimum field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



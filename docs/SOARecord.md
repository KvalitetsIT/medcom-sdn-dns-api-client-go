# SOARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MName** | **string** | Primary master nameserver for the zone. | 
**RName** | **string** | Responsible party email (encoded format). | 
**Serial** | **int32** |  | 
**Refresh** | **int32** |  | 
**Retry** | **int32** |  | 
**Expire** | **int32** |  | 
**Minimum** | **int32** |  | 

## Methods

### NewSOARecord

`func NewSOARecord(mName string, rName string, serial int32, refresh int32, retry int32, expire int32, minimum int32, ) *SOARecord`

NewSOARecord instantiates a new SOARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSOARecordWithDefaults

`func NewSOARecordWithDefaults() *SOARecord`

NewSOARecordWithDefaults instantiates a new SOARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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



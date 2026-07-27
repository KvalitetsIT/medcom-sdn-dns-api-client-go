# SOARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Fqdn** | **string** | Fully qualified domain name | 
**Type** | **string** | DNS record type discriminator. | 
**Source** | **string** | Identifies the system, service, or user that created the DNS record. This field is used for auditing, traceability, and ownership purposes. Typical values include the name of an automation system, application, integration, or a user identifier | 
**MName** | **string** | Primary master nameserver for the zone. | 
**RName** | **string** | Responsible party email (encoded format). | 
**Serial** | **int64** |  | 
**Refresh** | **int32** |  | 
**Retry** | **int32** |  | 
**Expire** | **int32** |  | 
**Minimum** | **int32** |  | 

## Methods

### NewSOARecord

`func NewSOARecord(fqdn string, type_ string, source string, mName string, rName string, serial int64, refresh int32, retry int32, expire int32, minimum int32, ) *SOARecord`

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

### GetFqdn

`func (o *SOARecord) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *SOARecord) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *SOARecord) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.


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


### GetSource

`func (o *SOARecord) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SOARecord) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SOARecord) SetSource(v string)`

SetSource sets Source field to given value.


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

`func (o *SOARecord) GetSerial() int64`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *SOARecord) GetSerialOk() (*int64, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *SOARecord) SetSerial(v int64)`

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



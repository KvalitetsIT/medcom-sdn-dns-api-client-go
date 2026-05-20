# AAAARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | the host associated with the ipv4. | 
**Ipv6** | **string** | IPv6 address assigned to the hostname. | 

## Methods

### NewAAAARecord

`func NewAAAARecord(host string, ipv6 string, ) *AAAARecord`

NewAAAARecord instantiates a new AAAARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAAAARecordWithDefaults

`func NewAAAARecordWithDefaults() *AAAARecord`

NewAAAARecordWithDefaults instantiates a new AAAARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *AAAARecord) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *AAAARecord) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *AAAARecord) SetHost(v string)`

SetHost sets Host field to given value.


### GetIpv6

`func (o *AAAARecord) GetIpv6() string`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *AAAARecord) GetIpv6Ok() (*string, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *AAAARecord) SetIpv6(v string)`

SetIpv6 sets Ipv6 field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



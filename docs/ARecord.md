# ARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | the host associated with the ipv4. | 
**Ipv4** | **string** | IPv4 address assigned to the hostname. | 

## Methods

### NewARecord

`func NewARecord(host string, ipv4 string, ) *ARecord`

NewARecord instantiates a new ARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewARecordWithDefaults

`func NewARecordWithDefaults() *ARecord`

NewARecordWithDefaults instantiates a new ARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *ARecord) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *ARecord) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *ARecord) SetHost(v string)`

SetHost sets Host field to given value.


### GetIpv4

`func (o *ARecord) GetIpv4() string`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *ARecord) GetIpv4Ok() (*string, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *ARecord) SetIpv4(v string)`

SetIpv4 sets Ipv4 field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



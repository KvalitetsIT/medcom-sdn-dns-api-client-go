# AAAARecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Fqdn** | **string** | Fully qualified domain name | 
**Type** | **string** | DNS record type discriminator. | 
**Source** | **string** | Identifies the system, service, or user that created the DNS record. This field is used for auditing, traceability, and ownership purposes. Typical values include the name of an automation system, application, integration, or a user identifier | 
**Ipv6** | **string** | IPv6 address assigned to the hostname. | 

## Methods

### NewAAAARecord

`func NewAAAARecord(fqdn string, type_ string, source string, ipv6 string, ) *AAAARecord`

NewAAAARecord instantiates a new AAAARecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAAAARecordWithDefaults

`func NewAAAARecordWithDefaults() *AAAARecord`

NewAAAARecordWithDefaults instantiates a new AAAARecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AAAARecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AAAARecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AAAARecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AAAARecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFqdn

`func (o *AAAARecord) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *AAAARecord) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *AAAARecord) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.


### GetType

`func (o *AAAARecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AAAARecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AAAARecord) SetType(v string)`

SetType sets Type field to given value.


### GetSource

`func (o *AAAARecord) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AAAARecord) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AAAARecord) SetSource(v string)`

SetSource sets Source field to given value.


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



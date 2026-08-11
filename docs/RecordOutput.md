# RecordOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Fqdn** | **string** | Fully qualified domain name | 
**Type** | **string** | DNS record type discriminator. | 
**Source** | **string** | Identifies the system, service, or user that created the DNS record. This field is used for auditing, traceability, and ownership purposes. Typical values include the name of an automation system, application, integration, or a user identifier | 
**Ipv4** | **string** | IPv4 address assigned to the hostname. | 
**Ipv6** | **string** | IPv6 address assigned to the hostname. | 
**Target** | **string** | Target hostname providing the service. | 
**Priority** | **int32** | Service priority where lower values are preferred. | 
**Exchange** | **string** | Mail server hostname. | 
**Value** | **string** | Certificate authority authorization value. | 
**Nameserver** | **string** | Authoritative nameserver hostname. | 
**MName** | **string** | Primary master nameserver for the zone. | 
**RName** | **string** | Responsible party email (encoded format). | 
**Serial** | **int64** |  | 
**Refresh** | **int32** |  | 
**Retry** | **int32** |  | 
**Expire** | **int32** |  | 
**Minimum** | **int32** |  | 
**Weight** | **int32** | Relative weight for load balancing between services with the same priority. | 
**Port** | **int32** | Network port exposed by the target service. | 
**Pointer** | **string** | Reverse DNS hostname target. | 
**Flags** | **int32** | Flags controlling record interpretation. | 
**Tag** | **string** | CAA property tag defining the authorization behavior. | 

## Methods

### NewRecordOutput

`func NewRecordOutput(fqdn string, type_ string, source string, ipv4 string, ipv6 string, target string, priority int32, exchange string, value string, nameserver string, mName string, rName string, serial int64, refresh int32, retry int32, expire int32, minimum int32, weight int32, port int32, pointer string, flags int32, tag string, ) *RecordOutput`

NewRecordOutput instantiates a new RecordOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordOutputWithDefaults

`func NewRecordOutputWithDefaults() *RecordOutput`

NewRecordOutputWithDefaults instantiates a new RecordOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecordOutput) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecordOutput) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecordOutput) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *RecordOutput) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFqdn

`func (o *RecordOutput) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *RecordOutput) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *RecordOutput) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.


### GetType

`func (o *RecordOutput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RecordOutput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RecordOutput) SetType(v string)`

SetType sets Type field to given value.


### GetSource

`func (o *RecordOutput) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RecordOutput) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RecordOutput) SetSource(v string)`

SetSource sets Source field to given value.


### GetIpv4

`func (o *RecordOutput) GetIpv4() string`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *RecordOutput) GetIpv4Ok() (*string, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *RecordOutput) SetIpv4(v string)`

SetIpv4 sets Ipv4 field to given value.


### GetIpv6

`func (o *RecordOutput) GetIpv6() string`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *RecordOutput) GetIpv6Ok() (*string, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *RecordOutput) SetIpv6(v string)`

SetIpv6 sets Ipv6 field to given value.


### GetTarget

`func (o *RecordOutput) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *RecordOutput) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *RecordOutput) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetPriority

`func (o *RecordOutput) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *RecordOutput) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *RecordOutput) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetExchange

`func (o *RecordOutput) GetExchange() string`

GetExchange returns the Exchange field if non-nil, zero value otherwise.

### GetExchangeOk

`func (o *RecordOutput) GetExchangeOk() (*string, bool)`

GetExchangeOk returns a tuple with the Exchange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchange

`func (o *RecordOutput) SetExchange(v string)`

SetExchange sets Exchange field to given value.


### GetValue

`func (o *RecordOutput) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *RecordOutput) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *RecordOutput) SetValue(v string)`

SetValue sets Value field to given value.


### GetNameserver

`func (o *RecordOutput) GetNameserver() string`

GetNameserver returns the Nameserver field if non-nil, zero value otherwise.

### GetNameserverOk

`func (o *RecordOutput) GetNameserverOk() (*string, bool)`

GetNameserverOk returns a tuple with the Nameserver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameserver

`func (o *RecordOutput) SetNameserver(v string)`

SetNameserver sets Nameserver field to given value.


### GetMName

`func (o *RecordOutput) GetMName() string`

GetMName returns the MName field if non-nil, zero value otherwise.

### GetMNameOk

`func (o *RecordOutput) GetMNameOk() (*string, bool)`

GetMNameOk returns a tuple with the MName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMName

`func (o *RecordOutput) SetMName(v string)`

SetMName sets MName field to given value.


### GetRName

`func (o *RecordOutput) GetRName() string`

GetRName returns the RName field if non-nil, zero value otherwise.

### GetRNameOk

`func (o *RecordOutput) GetRNameOk() (*string, bool)`

GetRNameOk returns a tuple with the RName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRName

`func (o *RecordOutput) SetRName(v string)`

SetRName sets RName field to given value.


### GetSerial

`func (o *RecordOutput) GetSerial() int64`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *RecordOutput) GetSerialOk() (*int64, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *RecordOutput) SetSerial(v int64)`

SetSerial sets Serial field to given value.


### GetRefresh

`func (o *RecordOutput) GetRefresh() int32`

GetRefresh returns the Refresh field if non-nil, zero value otherwise.

### GetRefreshOk

`func (o *RecordOutput) GetRefreshOk() (*int32, bool)`

GetRefreshOk returns a tuple with the Refresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefresh

`func (o *RecordOutput) SetRefresh(v int32)`

SetRefresh sets Refresh field to given value.


### GetRetry

`func (o *RecordOutput) GetRetry() int32`

GetRetry returns the Retry field if non-nil, zero value otherwise.

### GetRetryOk

`func (o *RecordOutput) GetRetryOk() (*int32, bool)`

GetRetryOk returns a tuple with the Retry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetry

`func (o *RecordOutput) SetRetry(v int32)`

SetRetry sets Retry field to given value.


### GetExpire

`func (o *RecordOutput) GetExpire() int32`

GetExpire returns the Expire field if non-nil, zero value otherwise.

### GetExpireOk

`func (o *RecordOutput) GetExpireOk() (*int32, bool)`

GetExpireOk returns a tuple with the Expire field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpire

`func (o *RecordOutput) SetExpire(v int32)`

SetExpire sets Expire field to given value.


### GetMinimum

`func (o *RecordOutput) GetMinimum() int32`

GetMinimum returns the Minimum field if non-nil, zero value otherwise.

### GetMinimumOk

`func (o *RecordOutput) GetMinimumOk() (*int32, bool)`

GetMinimumOk returns a tuple with the Minimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimum

`func (o *RecordOutput) SetMinimum(v int32)`

SetMinimum sets Minimum field to given value.


### GetWeight

`func (o *RecordOutput) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *RecordOutput) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *RecordOutput) SetWeight(v int32)`

SetWeight sets Weight field to given value.


### GetPort

`func (o *RecordOutput) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *RecordOutput) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *RecordOutput) SetPort(v int32)`

SetPort sets Port field to given value.


### GetPointer

`func (o *RecordOutput) GetPointer() string`

GetPointer returns the Pointer field if non-nil, zero value otherwise.

### GetPointerOk

`func (o *RecordOutput) GetPointerOk() (*string, bool)`

GetPointerOk returns a tuple with the Pointer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPointer

`func (o *RecordOutput) SetPointer(v string)`

SetPointer sets Pointer field to given value.


### GetFlags

`func (o *RecordOutput) GetFlags() int32`

GetFlags returns the Flags field if non-nil, zero value otherwise.

### GetFlagsOk

`func (o *RecordOutput) GetFlagsOk() (*int32, bool)`

GetFlagsOk returns a tuple with the Flags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlags

`func (o *RecordOutput) SetFlags(v int32)`

SetFlags sets Flags field to given value.


### GetTag

`func (o *RecordOutput) GetTag() string`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *RecordOutput) GetTagOk() (*string, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *RecordOutput) SetTag(v string)`

SetTag sets Tag field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



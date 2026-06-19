# Record

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Ttl** | Pointer to **int32** | DNS Time To Live in seconds. | [optional] 
**Type** | **string** | DNS record type discriminator. | 
**Host** | **string** | Alias hostname | 
**Ipv4** | **string** | IPv4 address assigned to the hostname. | 
**Ipv6** | **string** | IPv6 address assigned to the hostname. | 
**CanonicalName** | **string** | Canonical hostname target. | 
**Priority** | **int32** | Service priority where lower values are preferred. | 
**Exchange** | **string** | Mail server hostname. | 
**Key** | **string** | TXT record key. | 
**Value** | **string** | Certificate authority authorization value. | 
**Name** | **string** | key/name. | 
**Nameserver** | **string** | Authoritative nameserver hostname. | 
**MName** | **string** | Primary master nameserver for the zone. | 
**RName** | **string** | Responsible party email (encoded format). | 
**Serial** | **int32** |  | 
**Refresh** | **int32** |  | 
**Retry** | **int32** |  | 
**Expire** | **int32** |  | 
**Minimum** | **int32** |  | 
**Weight** | **int32** | Relative weight for load balancing between services with the same priority. | 
**Port** | **int32** | Network port exposed by the target service. | 
**Target** | **string** | Target hostname providing the service. | 
**Pointer** | **string** | Reverse DNS hostname target. | 
**Flags** | **int32** | Flags controlling record interpretation. | 
**Tag** | **string** | CAA property tag defining the authorization behavior. | 

## Methods

### NewRecord

`func NewRecord(type_ string, host string, ipv4 string, ipv6 string, canonicalName string, priority int32, exchange string, key string, value string, name string, nameserver string, mName string, rName string, serial int32, refresh int32, retry int32, expire int32, minimum int32, weight int32, port int32, target string, pointer string, flags int32, tag string, ) *Record`

NewRecord instantiates a new Record object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordWithDefaults

`func NewRecordWithDefaults() *Record`

NewRecordWithDefaults instantiates a new Record object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Record) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Record) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Record) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Record) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTtl

`func (o *Record) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *Record) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *Record) SetTtl(v int32)`

SetTtl sets Ttl field to given value.

### HasTtl

`func (o *Record) HasTtl() bool`

HasTtl returns a boolean if a field has been set.

### GetType

`func (o *Record) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Record) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Record) SetType(v string)`

SetType sets Type field to given value.


### GetHost

`func (o *Record) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *Record) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *Record) SetHost(v string)`

SetHost sets Host field to given value.


### GetIpv4

`func (o *Record) GetIpv4() string`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *Record) GetIpv4Ok() (*string, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *Record) SetIpv4(v string)`

SetIpv4 sets Ipv4 field to given value.


### GetIpv6

`func (o *Record) GetIpv6() string`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *Record) GetIpv6Ok() (*string, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *Record) SetIpv6(v string)`

SetIpv6 sets Ipv6 field to given value.


### GetCanonicalName

`func (o *Record) GetCanonicalName() string`

GetCanonicalName returns the CanonicalName field if non-nil, zero value otherwise.

### GetCanonicalNameOk

`func (o *Record) GetCanonicalNameOk() (*string, bool)`

GetCanonicalNameOk returns a tuple with the CanonicalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalName

`func (o *Record) SetCanonicalName(v string)`

SetCanonicalName sets CanonicalName field to given value.


### GetPriority

`func (o *Record) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *Record) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *Record) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetExchange

`func (o *Record) GetExchange() string`

GetExchange returns the Exchange field if non-nil, zero value otherwise.

### GetExchangeOk

`func (o *Record) GetExchangeOk() (*string, bool)`

GetExchangeOk returns a tuple with the Exchange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchange

`func (o *Record) SetExchange(v string)`

SetExchange sets Exchange field to given value.


### GetKey

`func (o *Record) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *Record) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *Record) SetKey(v string)`

SetKey sets Key field to given value.


### GetValue

`func (o *Record) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *Record) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *Record) SetValue(v string)`

SetValue sets Value field to given value.


### GetName

`func (o *Record) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Record) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Record) SetName(v string)`

SetName sets Name field to given value.


### GetNameserver

`func (o *Record) GetNameserver() string`

GetNameserver returns the Nameserver field if non-nil, zero value otherwise.

### GetNameserverOk

`func (o *Record) GetNameserverOk() (*string, bool)`

GetNameserverOk returns a tuple with the Nameserver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameserver

`func (o *Record) SetNameserver(v string)`

SetNameserver sets Nameserver field to given value.


### GetMName

`func (o *Record) GetMName() string`

GetMName returns the MName field if non-nil, zero value otherwise.

### GetMNameOk

`func (o *Record) GetMNameOk() (*string, bool)`

GetMNameOk returns a tuple with the MName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMName

`func (o *Record) SetMName(v string)`

SetMName sets MName field to given value.


### GetRName

`func (o *Record) GetRName() string`

GetRName returns the RName field if non-nil, zero value otherwise.

### GetRNameOk

`func (o *Record) GetRNameOk() (*string, bool)`

GetRNameOk returns a tuple with the RName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRName

`func (o *Record) SetRName(v string)`

SetRName sets RName field to given value.


### GetSerial

`func (o *Record) GetSerial() int32`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *Record) GetSerialOk() (*int32, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *Record) SetSerial(v int32)`

SetSerial sets Serial field to given value.


### GetRefresh

`func (o *Record) GetRefresh() int32`

GetRefresh returns the Refresh field if non-nil, zero value otherwise.

### GetRefreshOk

`func (o *Record) GetRefreshOk() (*int32, bool)`

GetRefreshOk returns a tuple with the Refresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefresh

`func (o *Record) SetRefresh(v int32)`

SetRefresh sets Refresh field to given value.


### GetRetry

`func (o *Record) GetRetry() int32`

GetRetry returns the Retry field if non-nil, zero value otherwise.

### GetRetryOk

`func (o *Record) GetRetryOk() (*int32, bool)`

GetRetryOk returns a tuple with the Retry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetry

`func (o *Record) SetRetry(v int32)`

SetRetry sets Retry field to given value.


### GetExpire

`func (o *Record) GetExpire() int32`

GetExpire returns the Expire field if non-nil, zero value otherwise.

### GetExpireOk

`func (o *Record) GetExpireOk() (*int32, bool)`

GetExpireOk returns a tuple with the Expire field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpire

`func (o *Record) SetExpire(v int32)`

SetExpire sets Expire field to given value.


### GetMinimum

`func (o *Record) GetMinimum() int32`

GetMinimum returns the Minimum field if non-nil, zero value otherwise.

### GetMinimumOk

`func (o *Record) GetMinimumOk() (*int32, bool)`

GetMinimumOk returns a tuple with the Minimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimum

`func (o *Record) SetMinimum(v int32)`

SetMinimum sets Minimum field to given value.


### GetWeight

`func (o *Record) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *Record) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *Record) SetWeight(v int32)`

SetWeight sets Weight field to given value.


### GetPort

`func (o *Record) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *Record) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *Record) SetPort(v int32)`

SetPort sets Port field to given value.


### GetTarget

`func (o *Record) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *Record) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *Record) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetPointer

`func (o *Record) GetPointer() string`

GetPointer returns the Pointer field if non-nil, zero value otherwise.

### GetPointerOk

`func (o *Record) GetPointerOk() (*string, bool)`

GetPointerOk returns a tuple with the Pointer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPointer

`func (o *Record) SetPointer(v string)`

SetPointer sets Pointer field to given value.


### GetFlags

`func (o *Record) GetFlags() int32`

GetFlags returns the Flags field if non-nil, zero value otherwise.

### GetFlagsOk

`func (o *Record) GetFlagsOk() (*int32, bool)`

GetFlagsOk returns a tuple with the Flags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlags

`func (o *Record) SetFlags(v int32)`

SetFlags sets Flags field to given value.


### GetTag

`func (o *Record) GetTag() string`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *Record) GetTagOk() (*string, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *Record) SetTag(v string)`

SetTag sets Tag field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



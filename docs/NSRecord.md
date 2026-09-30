# NSRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Fqdn** | **string** | Fully qualified domain name | 
**Type** | **string** | DNS record type discriminator. | 
**Source** | **string** | Identifies the system, service, or user that created the DNS record. This field is used for auditing, traceability, and ownership purposes. Typical values include the name of an automation system, application, integration, or a user identifier | 
**Nameserver** | **string** | Authoritative nameserver hostname. | 

## Methods

### NewNSRecord

`func NewNSRecord(fqdn string, type_ string, source string, nameserver string, ) *NSRecord`

NewNSRecord instantiates a new NSRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNSRecordWithDefaults

`func NewNSRecordWithDefaults() *NSRecord`

NewNSRecordWithDefaults instantiates a new NSRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *NSRecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NSRecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NSRecord) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *NSRecord) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFqdn

`func (o *NSRecord) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *NSRecord) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *NSRecord) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.


### GetType

`func (o *NSRecord) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NSRecord) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NSRecord) SetType(v string)`

SetType sets Type field to given value.


### GetSource

`func (o *NSRecord) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *NSRecord) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *NSRecord) SetSource(v string)`

SetSource sets Source field to given value.


### GetNameserver

`func (o *NSRecord) GetNameserver() string`

GetNameserver returns the Nameserver field if non-nil, zero value otherwise.

### GetNameserverOk

`func (o *NSRecord) GetNameserverOk() (*string, bool)`

GetNameserverOk returns a tuple with the Nameserver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameserver

`func (o *NSRecord) SetNameserver(v string)`

SetNameserver sets Nameserver field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



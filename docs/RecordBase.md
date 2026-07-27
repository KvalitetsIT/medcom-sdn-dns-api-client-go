# RecordBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID v4 associated with the DNS record. | [optional] 
**Fqdn** | **string** | Fully qualified domain name | 
**Type** | **string** | DNS record type discriminator. | 
**Source** | **string** | Identifies the system, service, or user that created the DNS record. This field is used for auditing, traceability, and ownership purposes. Typical values include the name of an automation system, application, integration, or a user identifier | 

## Methods

### NewRecordBase

`func NewRecordBase(fqdn string, type_ string, source string, ) *RecordBase`

NewRecordBase instantiates a new RecordBase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordBaseWithDefaults

`func NewRecordBaseWithDefaults() *RecordBase`

NewRecordBaseWithDefaults instantiates a new RecordBase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecordBase) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecordBase) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecordBase) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *RecordBase) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFqdn

`func (o *RecordBase) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *RecordBase) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *RecordBase) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.


### GetType

`func (o *RecordBase) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RecordBase) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RecordBase) SetType(v string)`

SetType sets Type field to given value.


### GetSource

`func (o *RecordBase) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RecordBase) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RecordBase) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



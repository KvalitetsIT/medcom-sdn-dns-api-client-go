# SRVRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Priority** | **int32** | Service priority where lower values are preferred. | 
**Weight** | **int32** | Relative weight for load balancing between services with the same priority. | 
**Port** | **int32** | Network port exposed by the target service. | 
**Target** | **string** | Target hostname providing the service. | 

## Methods

### NewSRVRecord

`func NewSRVRecord(priority int32, weight int32, port int32, target string, ) *SRVRecord`

NewSRVRecord instantiates a new SRVRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSRVRecordWithDefaults

`func NewSRVRecordWithDefaults() *SRVRecord`

NewSRVRecordWithDefaults instantiates a new SRVRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPriority

`func (o *SRVRecord) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *SRVRecord) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *SRVRecord) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetWeight

`func (o *SRVRecord) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *SRVRecord) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *SRVRecord) SetWeight(v int32)`

SetWeight sets Weight field to given value.


### GetPort

`func (o *SRVRecord) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *SRVRecord) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *SRVRecord) SetPort(v int32)`

SetPort sets Port field to given value.


### GetTarget

`func (o *SRVRecord) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *SRVRecord) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *SRVRecord) SetTarget(v string)`

SetTarget sets Target field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



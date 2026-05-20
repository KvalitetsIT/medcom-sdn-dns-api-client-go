# BasicError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorCode** | **int32** | Application-specific error code. | 
**Error** | **string** | Human-readable error message. | 
**Path** | **string** | Request path that caused the error. | 
**Status** | **int32** | HTTP status code. | 
**StatusText** | **string** | HTTP status text. | 
**Timestamp** | **time.Time** | Timestamp when the error occurred. | 

## Methods

### NewBasicError

`func NewBasicError(errorCode int32, error_ string, path string, status int32, statusText string, timestamp time.Time, ) *BasicError`

NewBasicError instantiates a new BasicError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBasicErrorWithDefaults

`func NewBasicErrorWithDefaults() *BasicError`

NewBasicErrorWithDefaults instantiates a new BasicError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorCode

`func (o *BasicError) GetErrorCode() int32`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *BasicError) GetErrorCodeOk() (*int32, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *BasicError) SetErrorCode(v int32)`

SetErrorCode sets ErrorCode field to given value.


### GetError

`func (o *BasicError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BasicError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BasicError) SetError(v string)`

SetError sets Error field to given value.


### GetPath

`func (o *BasicError) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *BasicError) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *BasicError) SetPath(v string)`

SetPath sets Path field to given value.


### GetStatus

`func (o *BasicError) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BasicError) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BasicError) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetStatusText

`func (o *BasicError) GetStatusText() string`

GetStatusText returns the StatusText field if non-nil, zero value otherwise.

### GetStatusTextOk

`func (o *BasicError) GetStatusTextOk() (*string, bool)`

GetStatusTextOk returns a tuple with the StatusText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusText

`func (o *BasicError) SetStatusText(v string)`

SetStatusText sets StatusText field to given value.


### GetTimestamp

`func (o *BasicError) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *BasicError) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *BasicError) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



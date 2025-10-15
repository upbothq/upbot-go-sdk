# UpdateTheSpecifiedResourceInStorageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Must not be greater than 255 characters. | [optional] 
**Target** | Pointer to **NullableString** | Must not be greater than 500 characters. | [optional] 
**Interval** | Pointer to **string** |  | [optional] 
**RetryCount** | Pointer to **NullableInt32** | Must be at least 0. Must not be greater than 10. | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Bot** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUpdateTheSpecifiedResourceInStorageRequest

`func NewUpdateTheSpecifiedResourceInStorageRequest() *UpdateTheSpecifiedResourceInStorageRequest`

NewUpdateTheSpecifiedResourceInStorageRequest instantiates a new UpdateTheSpecifiedResourceInStorageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTheSpecifiedResourceInStorageRequestWithDefaults

`func NewUpdateTheSpecifiedResourceInStorageRequestWithDefaults() *UpdateTheSpecifiedResourceInStorageRequest`

NewUpdateTheSpecifiedResourceInStorageRequestWithDefaults instantiates a new UpdateTheSpecifiedResourceInStorageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTarget

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### SetTargetNil

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetTargetNil(b bool)`

 SetTargetNil sets the value for Target to be an explicit nil

### UnsetTarget
`func (o *UpdateTheSpecifiedResourceInStorageRequest) UnsetTarget()`

UnsetTarget ensures that no value is present for Target, not even an explicit nil
### GetInterval

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetInterval(v string)`

SetInterval sets Interval field to given value.

### HasInterval

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasInterval() bool`

HasInterval returns a boolean if a field has been set.

### GetRetryCount

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetRetryCount() int32`

GetRetryCount returns the RetryCount field if non-nil, zero value otherwise.

### GetRetryCountOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetRetryCountOk() (*int32, bool)`

GetRetryCountOk returns a tuple with the RetryCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryCount

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetRetryCount(v int32)`

SetRetryCount sets RetryCount field to given value.

### HasRetryCount

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasRetryCount() bool`

HasRetryCount returns a boolean if a field has been set.

### SetRetryCountNil

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetRetryCountNil(b bool)`

 SetRetryCountNil sets the value for RetryCount to be an explicit nil

### UnsetRetryCount
`func (o *UpdateTheSpecifiedResourceInStorageRequest) UnsetRetryCount()`

UnsetRetryCount ensures that no value is present for RetryCount, not even an explicit nil
### GetIsActive

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetType

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetBot

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetBot() []string`

GetBot returns the Bot field if non-nil, zero value otherwise.

### GetBotOk

`func (o *UpdateTheSpecifiedResourceInStorageRequest) GetBotOk() (*[]string, bool)`

GetBotOk returns a tuple with the Bot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBot

`func (o *UpdateTheSpecifiedResourceInStorageRequest) SetBot(v []string)`

SetBot sets Bot field to given value.

### HasBot

`func (o *UpdateTheSpecifiedResourceInStorageRequest) HasBot() bool`

HasBot returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



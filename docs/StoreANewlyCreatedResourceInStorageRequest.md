# StoreANewlyCreatedResourceInStorageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | This field is required unless &lt;code&gt;type&lt;/code&gt; is in &lt;code&gt;discord_bot&lt;/code&gt;. Must not be greater than 255 characters. | [optional] 
**Type** | **string** |  | 
**Target** | Pointer to **string** | This field is required unless &lt;code&gt;type&lt;/code&gt; is in &lt;code&gt;discord_bot&lt;/code&gt;. Must not be greater than 255 characters. | [optional] 
**RetryCount** | Pointer to **NullableInt32** | This field is required unless &lt;code&gt;type&lt;/code&gt; is in &lt;code&gt;discord_bot&lt;/code&gt;. Must be at least 0. Must not be greater than 10. | [optional] 
**Interval** | Pointer to **string** | This field is required unless &lt;code&gt;type&lt;/code&gt; is in &lt;code&gt;discord_bot&lt;/code&gt;. | [optional] 
**Bot** | Pointer to [**StoreANewlyCreatedResourceInStorageRequestBot**](StoreANewlyCreatedResourceInStorageRequestBot.md) |  | [optional] 

## Methods

### NewStoreANewlyCreatedResourceInStorageRequest

`func NewStoreANewlyCreatedResourceInStorageRequest(type_ string, ) *StoreANewlyCreatedResourceInStorageRequest`

NewStoreANewlyCreatedResourceInStorageRequest instantiates a new StoreANewlyCreatedResourceInStorageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreANewlyCreatedResourceInStorageRequestWithDefaults

`func NewStoreANewlyCreatedResourceInStorageRequestWithDefaults() *StoreANewlyCreatedResourceInStorageRequest`

NewStoreANewlyCreatedResourceInStorageRequestWithDefaults instantiates a new StoreANewlyCreatedResourceInStorageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *StoreANewlyCreatedResourceInStorageRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetType(v string)`

SetType sets Type field to given value.


### GetTarget

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *StoreANewlyCreatedResourceInStorageRequest) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetRetryCount

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetRetryCount() int32`

GetRetryCount returns the RetryCount field if non-nil, zero value otherwise.

### GetRetryCountOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetRetryCountOk() (*int32, bool)`

GetRetryCountOk returns a tuple with the RetryCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryCount

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetRetryCount(v int32)`

SetRetryCount sets RetryCount field to given value.

### HasRetryCount

`func (o *StoreANewlyCreatedResourceInStorageRequest) HasRetryCount() bool`

HasRetryCount returns a boolean if a field has been set.

### SetRetryCountNil

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetRetryCountNil(b bool)`

 SetRetryCountNil sets the value for RetryCount to be an explicit nil

### UnsetRetryCount
`func (o *StoreANewlyCreatedResourceInStorageRequest) UnsetRetryCount()`

UnsetRetryCount ensures that no value is present for RetryCount, not even an explicit nil
### GetInterval

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetInterval(v string)`

SetInterval sets Interval field to given value.

### HasInterval

`func (o *StoreANewlyCreatedResourceInStorageRequest) HasInterval() bool`

HasInterval returns a boolean if a field has been set.

### GetBot

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetBot() StoreANewlyCreatedResourceInStorageRequestBot`

GetBot returns the Bot field if non-nil, zero value otherwise.

### GetBotOk

`func (o *StoreANewlyCreatedResourceInStorageRequest) GetBotOk() (*StoreANewlyCreatedResourceInStorageRequestBot, bool)`

GetBotOk returns a tuple with the Bot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBot

`func (o *StoreANewlyCreatedResourceInStorageRequest) SetBot(v StoreANewlyCreatedResourceInStorageRequestBot)`

SetBot sets Bot field to given value.

### HasBot

`func (o *StoreANewlyCreatedResourceInStorageRequest) HasBot() bool`

HasBot returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



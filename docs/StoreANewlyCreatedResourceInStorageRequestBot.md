# StoreANewlyCreatedResourceInStorageRequestBot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DiscordBotId** | Pointer to **string** | This field is required when &lt;code&gt;type&lt;/code&gt; is &lt;code&gt;discord_bot&lt;/code&gt;. Must match the regex /^\\d{17,19}$/. | [optional] 
**DiscordGuildId** | Pointer to **string** | This field is required when &lt;code&gt;type&lt;/code&gt; is &lt;code&gt;discord_bot&lt;/code&gt;. Must match the regex /^\\d{17,19}$/. | [optional] 

## Methods

### NewStoreANewlyCreatedResourceInStorageRequestBot

`func NewStoreANewlyCreatedResourceInStorageRequestBot() *StoreANewlyCreatedResourceInStorageRequestBot`

NewStoreANewlyCreatedResourceInStorageRequestBot instantiates a new StoreANewlyCreatedResourceInStorageRequestBot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreANewlyCreatedResourceInStorageRequestBotWithDefaults

`func NewStoreANewlyCreatedResourceInStorageRequestBotWithDefaults() *StoreANewlyCreatedResourceInStorageRequestBot`

NewStoreANewlyCreatedResourceInStorageRequestBotWithDefaults instantiates a new StoreANewlyCreatedResourceInStorageRequestBot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDiscordBotId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) GetDiscordBotId() string`

GetDiscordBotId returns the DiscordBotId field if non-nil, zero value otherwise.

### GetDiscordBotIdOk

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) GetDiscordBotIdOk() (*string, bool)`

GetDiscordBotIdOk returns a tuple with the DiscordBotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordBotId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) SetDiscordBotId(v string)`

SetDiscordBotId sets DiscordBotId field to given value.

### HasDiscordBotId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) HasDiscordBotId() bool`

HasDiscordBotId returns a boolean if a field has been set.

### GetDiscordGuildId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) GetDiscordGuildId() string`

GetDiscordGuildId returns the DiscordGuildId field if non-nil, zero value otherwise.

### GetDiscordGuildIdOk

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) GetDiscordGuildIdOk() (*string, bool)`

GetDiscordGuildIdOk returns a tuple with the DiscordGuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscordGuildId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) SetDiscordGuildId(v string)`

SetDiscordGuildId sets DiscordGuildId field to given value.

### HasDiscordGuildId

`func (o *StoreANewlyCreatedResourceInStorageRequestBot) HasDiscordGuildId() bool`

HasDiscordGuildId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



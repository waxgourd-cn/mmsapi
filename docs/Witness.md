# Witness

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Addr** | Pointer to **string** |  | [optional] 
**CreateBlockTime** | Pointer to **int64** |  | [optional] 
**Payload** | Pointer to **interface{}** |  | [optional] 
**Score** | Pointer to **int64** |  | [optional] 
**Vote** | Pointer to **int64** |  | [optional] 

## Methods

### NewWitness

`func NewWitness() *Witness`

NewWitness instantiates a new Witness object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWitnessWithDefaults

`func NewWitnessWithDefaults() *Witness`

NewWitnessWithDefaults instantiates a new Witness object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddr

`func (o *Witness) GetAddr() string`

GetAddr returns the Addr field if non-nil, zero value otherwise.

### GetAddrOk

`func (o *Witness) GetAddrOk() (*string, bool)`

GetAddrOk returns a tuple with the Addr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddr

`func (o *Witness) SetAddr(v string)`

SetAddr sets Addr field to given value.

### HasAddr

`func (o *Witness) HasAddr() bool`

HasAddr returns a boolean if a field has been set.

### GetCreateBlockTime

`func (o *Witness) GetCreateBlockTime() int64`

GetCreateBlockTime returns the CreateBlockTime field if non-nil, zero value otherwise.

### GetCreateBlockTimeOk

`func (o *Witness) GetCreateBlockTimeOk() (*int64, bool)`

GetCreateBlockTimeOk returns a tuple with the CreateBlockTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateBlockTime

`func (o *Witness) SetCreateBlockTime(v int64)`

SetCreateBlockTime sets CreateBlockTime field to given value.

### HasCreateBlockTime

`func (o *Witness) HasCreateBlockTime() bool`

HasCreateBlockTime returns a boolean if a field has been set.

### GetPayload

`func (o *Witness) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *Witness) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *Witness) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *Witness) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *Witness) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *Witness) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetScore

`func (o *Witness) GetScore() int64`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *Witness) GetScoreOk() (*int64, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *Witness) SetScore(v int64)`

SetScore sets Score field to given value.

### HasScore

`func (o *Witness) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetVote

`func (o *Witness) GetVote() int64`

GetVote returns the Vote field if non-nil, zero value otherwise.

### GetVoteOk

`func (o *Witness) GetVoteOk() (*int64, bool)`

GetVoteOk returns a tuple with the Vote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVote

`func (o *Witness) SetVote(v int64)`

SetVote sets Vote field to given value.

### HasVote

`func (o *Witness) HasVote() bool`

HasVote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



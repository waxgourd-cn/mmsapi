# ResponseBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]Witness**](Witness.md) |  | [optional] 

## Methods

### NewResponseBody

`func NewResponseBody() *ResponseBody`

NewResponseBody instantiates a new ResponseBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseBodyWithDefaults

`func NewResponseBodyWithDefaults() *ResponseBody`

NewResponseBodyWithDefaults instantiates a new ResponseBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ResponseBody) GetCode() int32`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ResponseBody) GetCodeOk() (*int32, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ResponseBody) SetCode(v int32)`

SetCode sets Code field to given value.

### HasCode

`func (o *ResponseBody) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetData

`func (o *ResponseBody) GetData() []Witness`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ResponseBody) GetDataOk() (*[]Witness, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ResponseBody) SetData(v []Witness)`

SetData sets Data field to given value.

### HasData

`func (o *ResponseBody) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



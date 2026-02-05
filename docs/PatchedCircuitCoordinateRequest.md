# PatchedCircuitCoordinateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**X** | Pointer to **int32** | X-coordinate of the device (horizontal) on the canvas. Smaller values correspond to a position further to the left on the monitor. | [optional] 
**Y** | Pointer to **int32** | Y-coordinate of the device (vertical) on the canvas. Smaller values correspond to a position further up on the monitor. | [optional] 

## Methods

### NewPatchedCircuitCoordinateRequest

`func NewPatchedCircuitCoordinateRequest() *PatchedCircuitCoordinateRequest`

NewPatchedCircuitCoordinateRequest instantiates a new PatchedCircuitCoordinateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchedCircuitCoordinateRequestWithDefaults

`func NewPatchedCircuitCoordinateRequestWithDefaults() *PatchedCircuitCoordinateRequest`

NewPatchedCircuitCoordinateRequestWithDefaults instantiates a new PatchedCircuitCoordinateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetX

`func (o *PatchedCircuitCoordinateRequest) GetX() int32`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *PatchedCircuitCoordinateRequest) GetXOk() (*int32, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *PatchedCircuitCoordinateRequest) SetX(v int32)`

SetX sets X field to given value.

### HasX

`func (o *PatchedCircuitCoordinateRequest) HasX() bool`

HasX returns a boolean if a field has been set.

### GetY

`func (o *PatchedCircuitCoordinateRequest) GetY() int32`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *PatchedCircuitCoordinateRequest) GetYOk() (*int32, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *PatchedCircuitCoordinateRequest) SetY(v int32)`

SetY sets Y field to given value.

### HasY

`func (o *PatchedCircuitCoordinateRequest) HasY() bool`

HasY returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



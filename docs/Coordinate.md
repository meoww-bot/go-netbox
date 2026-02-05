# Coordinate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**X** | **int32** | X-coordinate of the device (horizontal) on the canvas. Smaller values correspond to a position further to the left on the monitor. | 
**Y** | **int32** | Y-coordinate of the device (vertical) on the canvas. Smaller values correspond to a position further up on the monitor. | 

## Methods

### NewCoordinate

`func NewCoordinate(x int32, y int32, ) *Coordinate`

NewCoordinate instantiates a new Coordinate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCoordinateWithDefaults

`func NewCoordinateWithDefaults() *Coordinate`

NewCoordinateWithDefaults instantiates a new Coordinate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetX

`func (o *Coordinate) GetX() int32`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *Coordinate) GetXOk() (*int32, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *Coordinate) SetX(v int32)`

SetX sets X field to given value.


### GetY

`func (o *Coordinate) GetY() int32`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *Coordinate) GetYOk() (*int32, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *Coordinate) SetY(v int32)`

SetY sets Y field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



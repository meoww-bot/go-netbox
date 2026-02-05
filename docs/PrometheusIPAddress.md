# PrometheusIPAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Targets** | **string** |  | [readonly] 
**Labels** | **string** |  | [readonly] 

## Methods

### NewPrometheusIPAddress

`func NewPrometheusIPAddress(targets string, labels string, ) *PrometheusIPAddress`

NewPrometheusIPAddress instantiates a new PrometheusIPAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrometheusIPAddressWithDefaults

`func NewPrometheusIPAddressWithDefaults() *PrometheusIPAddress`

NewPrometheusIPAddressWithDefaults instantiates a new PrometheusIPAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTargets

`func (o *PrometheusIPAddress) GetTargets() string`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *PrometheusIPAddress) GetTargetsOk() (*string, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *PrometheusIPAddress) SetTargets(v string)`

SetTargets sets Targets field to given value.


### GetLabels

`func (o *PrometheusIPAddress) GetLabels() string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *PrometheusIPAddress) GetLabelsOk() (*string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *PrometheusIPAddress) SetLabels(v string)`

SetLabels sets Labels field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



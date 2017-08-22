# NulibMicroservices::DefaultApi

All URIs are relative to *https://hmv2sqwzhf.execute-api.us-east-1.amazonaws.com/staging*

Method | HTTP request | Description
------------- | ------------- | -------------
[**mint_id_get**](DefaultApi.md#mint_id_get) | **GET** /mintId | 


# **mint_id_get**
> MintIdResponse mint_id_get



### Example
```ruby
# load the gem
require 'nulib_microservices'
# setup authorization
NulibMicroservices.configure do |config|
  # Configure API key authorization: api_key
  config.api_key['x-api-key'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  #config.api_key_prefix['x-api-key'] = 'Bearer'
end

api_instance = NulibMicroservices::DefaultApi.new

begin
  result = api_instance.mint_id_get
  p result
rescue NulibMicroservices::ApiError => e
  puts "Exception when calling DefaultApi->mint_id_get: #{e}"
end
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**MintIdResponse**](MintIdResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json




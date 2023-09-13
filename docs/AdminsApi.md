# swagger_client.AdminsApi

All URIs are relative to *https://virtserver.swaggerhub.com/msmadds/blak/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_inventory**](AdminsApi.md#add_inventory) | **POST** /inventory | adds an inventory item

# **add_inventory**
> add_inventory(body=body)

adds an inventory item

Adds an item to the system

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.AdminsApi()
body = swagger_client.InventoryItem() # InventoryItem | Inventory item to add (optional)

try:
    # adds an inventory item
    api_instance.add_inventory(body=body)
except ApiException as e:
    print("Exception when calling AdminsApi->add_inventory: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**InventoryItem**](InventoryItem.md)| Inventory item to add | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


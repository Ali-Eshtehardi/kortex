# Message WifiConfigurationList

This page describes the C++ Kinova::Api::Base::WifiConfigurationList message.

## Overview / Purpose

Array of Wi-Fi configuration

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|wifi\_configuration\_list|Collection of [WifiConfiguration](msg_Base_WifiConfiguration.md#)|Wi-Fi configurations|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|wifi\_configuration\_list\_size\(\) const|int|void|Returns the number of elements currently in the field.|
|wifi\_configuration\_list\(\) const|const [WifiConfiguration](msg_Base_WifiConfiguration.md#)|int index|Returns the element at the given zero-based index. Calling this method with index outside of \[0, wifi\_configuration\_list\_size\(\)\) yields undefined behavior.|
|mutable\_wifi\_configuration\_list\(\)| [WifiConfiguration](msg_Base_WifiConfiguration.md#)\*|int index|Returns a pointer to the mutable [WifiConfiguration](msg_Base_WifiConfiguration.md#) object that stores the value of the element at the given zero-based index. Calling this method with index outside of \[0, wifi\_configuration\_list\_size\(\)\) yields undefined behavior.|
|add\_wifi\_configuration\_list\(\)| [WifiConfiguration](msg_Base_WifiConfiguration.md#)\*|void|Adds a new element and returns a pointer to it. The returned [WifiConfiguration](msg_Base_WifiConfiguration.md#) is mutable and will have none of its fields set \(i.e. it will be identical to a newly-allocated [WifiConfiguration](msg_Base_WifiConfiguration.md#)\).|
|clear\_wifi\_configuration\_list\(\)|void|void|Removes all elements from the field. After calling this, wifi\_configuration\_list\_size\(\) will return zero.|
|wifi\_configuration\_list\(\) const|const RepeatedPtrField< [WifiConfiguration](msg_Base_WifiConfiguration.md#)\>&|void|Returns the underlying RepeatedPtrField that stores the field's elements. This container class provides STL-like iterators and other methods.|
|mutable\_wifi\_configuration\_list\(\)|RepeatedPtrField< [WifiConfiguration](msg_Base_WifiConfiguration.md#)\>\*|void|Returns a pointer to the underlying mutable RepeatedPtrField that stores the field's elements. This container class provides STL-like iterators and other methods.|

**Parent topic:** [Base](../references/summary_Base.md)


# Message SafetyNotification

This page describes the C++ Kinova::Api::Common::SafetyNotification message.

## Overview / Purpose

Message that contains a safety event

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|safety\_handle| [SafetyHandle](msg_Common_SafetyHandle.md#)|Safety handle|
|value| [SafetyStatusValue](enm_Common_SafetyStatusValue.md#)|New safety status|
|timestamp| [Timestamp](msg_Common_Timestamp.md#)|Event timestamp|
|user\_handle| [UserProfileHandle](msg_Common_UserProfileHandle.md#)|User that caused the safety event|
|connection| [Connection](msg_Common_Connection.md#)|Connection that caused the safety event|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|has\_safety\_handle\(\) const|bool|void|Returns true if safety\_handle is set.|
|safety\_handle\(\)|const [SafetyHandle](msg_Common_SafetyHandle.md#)&|void|Returns the current value of safety\_handle. If safety\_handle is not set, returns a [SafetyHandle](msg_Common_SafetyHandle.md#) with none of its fields set \(possibly safety\_handle::default\_instance\(\)\).|
|mutable\_safety\_handle\(\)| [SafetyHandle](msg_Common_SafetyHandle.md#) \*|void|Returns a pointer to the mutable [SafetyHandle](msg_Common_SafetyHandle.md#) object that stores the field's value. If the field was not set prior to the call, then the returned [SafetyHandle](msg_Common_SafetyHandle.md#) will have none of its fields set \(i.e. it will be identical to a newly-allocated [SafetyHandle](msg_Common_SafetyHandle.md#)\). After calling this, has\_safety\_handle\(\) will return true and safety\_handle\(\) will return a reference to the same instance of [SafetyHandle](msg_Common_SafetyHandle.md#).|
|clear\_safety\_handle\(\)|void|void|Clears the value of the field. After calling this, has\_safety\_handle\(\) will return false and safety\_handle\(\) will return the default value.|
|set\_allocated\_safety\_handle\(\)|void| [SafetyHandle](msg_Common_SafetyHandle.md#) \*|Sets the [SafetyHandle](msg_Common_SafetyHandle.md#) object to the field and frees the previous field value if it exists. If the [SafetyHandle](msg_Common_SafetyHandle.md#) pointer is not NULL, the message takes ownership of the allocated [SafetyHandle](msg_Common_SafetyHandle.md#) object and has\_ [SafetyHandle](msg_Common_SafetyHandle.md#)\(\) will return true. Otherwise, if the safety\_handle is NULL, the behavior is the same as calling clear\_safety\_handle\(\).|
|release\_safety\_handle\(\)| [SafetyHandle](msg_Common_SafetyHandle.md#) \*|void|Releases the ownership of the field and returns the pointer of the [SafetyHandle](msg_Common_SafetyHandle.md#) object. After calling this, caller takes the ownership of the allocated [SafetyHandle](msg_Common_SafetyHandle.md#) object, has\_safety\_handle\(\) will return false, and safety\_handle\(\) will return the default value.|
|value\(\) const| [SafetyStatusValue](enm_Common_SafetyStatusValue.md#)|void|Returns the current value of value. If the value is not set, returns 0.|
|set\_value\(\)|void| [SafetyStatusValue](enm_Common_SafetyStatusValue.md#)|Sets the value of value. After calling this, value\(\) will return value.|
|clear\_value\(\)|void|void|Clears the value of value. After calling this, value\(\) will return the empty string/empty bytes.|
|has\_timestamp\(\) const|bool|void|Returns true if timestamp is set.|
|timestamp\(\)|const [Timestamp](msg_Common_Timestamp.md#)&|void|Returns the current value of timestamp. If timestamp is not set, returns a [Timestamp](msg_Common_Timestamp.md#) with none of its fields set \(possibly timestamp::default\_instance\(\)\).|
|mutable\_timestamp\(\)| [Timestamp](msg_Common_Timestamp.md#) \*|void|Returns a pointer to the mutable [Timestamp](msg_Common_Timestamp.md#) object that stores the field's value. If the field was not set prior to the call, then the returned [Timestamp](msg_Common_Timestamp.md#) will have none of its fields set \(i.e. it will be identical to a newly-allocated [Timestamp](msg_Common_Timestamp.md#)\). After calling this, has\_timestamp\(\) will return true and timestamp\(\) will return a reference to the same instance of [Timestamp](msg_Common_Timestamp.md#).|
|clear\_timestamp\(\)|void|void|Clears the value of the field. After calling this, has\_timestamp\(\) will return false and timestamp\(\) will return the default value.|
|set\_allocated\_timestamp\(\)|void| [Timestamp](msg_Common_Timestamp.md#) \*|Sets the [Timestamp](msg_Common_Timestamp.md#) object to the field and frees the previous field value if it exists. If the [Timestamp](msg_Common_Timestamp.md#) pointer is not NULL, the message takes ownership of the allocated [Timestamp](msg_Common_Timestamp.md#) object and has\_ [Timestamp](msg_Common_Timestamp.md#)\(\) will return true. Otherwise, if the timestamp is NULL, the behavior is the same as calling clear\_timestamp\(\).|
|release\_timestamp\(\)| [Timestamp](msg_Common_Timestamp.md#) \*|void|Releases the ownership of the field and returns the pointer of the [Timestamp](msg_Common_Timestamp.md#) object. After calling this, caller takes the ownership of the allocated [Timestamp](msg_Common_Timestamp.md#) object, has\_timestamp\(\) will return false, and timestamp\(\) will return the default value.|
|has\_user\_handle\(\) const|bool|void|Returns true if user\_handle is set.|
|user\_handle\(\)|const [UserProfileHandle](msg_Common_UserProfileHandle.md#)&|void|Returns the current value of user\_handle. If user\_handle is not set, returns a [UserProfileHandle](msg_Common_UserProfileHandle.md#) with none of its fields set \(possibly user\_handle::default\_instance\(\)\).|
|mutable\_user\_handle\(\)| [UserProfileHandle](msg_Common_UserProfileHandle.md#) \*|void|Returns a pointer to the mutable [UserProfileHandle](msg_Common_UserProfileHandle.md#) object that stores the field's value. If the field was not set prior to the call, then the returned [UserProfileHandle](msg_Common_UserProfileHandle.md#) will have none of its fields set \(i.e. it will be identical to a newly-allocated [UserProfileHandle](msg_Common_UserProfileHandle.md#)\). After calling this, has\_user\_handle\(\) will return true and user\_handle\(\) will return a reference to the same instance of [UserProfileHandle](msg_Common_UserProfileHandle.md#).|
|clear\_user\_handle\(\)|void|void|Clears the value of the field. After calling this, has\_user\_handle\(\) will return false and user\_handle\(\) will return the default value.|
|set\_allocated\_user\_handle\(\)|void| [UserProfileHandle](msg_Common_UserProfileHandle.md#) \*|Sets the [UserProfileHandle](msg_Common_UserProfileHandle.md#) object to the field and frees the previous field value if it exists. If the [UserProfileHandle](msg_Common_UserProfileHandle.md#) pointer is not NULL, the message takes ownership of the allocated [UserProfileHandle](msg_Common_UserProfileHandle.md#) object and has\_ [UserProfileHandle](msg_Common_UserProfileHandle.md#)\(\) will return true. Otherwise, if the user\_handle is NULL, the behavior is the same as calling clear\_user\_handle\(\).|
|release\_user\_handle\(\)| [UserProfileHandle](msg_Common_UserProfileHandle.md#) \*|void|Releases the ownership of the field and returns the pointer of the [UserProfileHandle](msg_Common_UserProfileHandle.md#) object. After calling this, caller takes the ownership of the allocated [UserProfileHandle](msg_Common_UserProfileHandle.md#) object, has\_user\_handle\(\) will return false, and user\_handle\(\) will return the default value.|
|has\_connection\(\) const|bool|void|Returns true if connection is set.|
|connection\(\)|const [Connection](msg_Common_Connection.md#)&|void|Returns the current value of connection. If connection is not set, returns a [Connection](msg_Common_Connection.md#) with none of its fields set \(possibly connection::default\_instance\(\)\).|
|mutable\_connection\(\)| [Connection](msg_Common_Connection.md#) \*|void|Returns a pointer to the mutable [Connection](msg_Common_Connection.md#) object that stores the field's value. If the field was not set prior to the call, then the returned [Connection](msg_Common_Connection.md#) will have none of its fields set \(i.e. it will be identical to a newly-allocated [Connection](msg_Common_Connection.md#)\). After calling this, has\_connection\(\) will return true and connection\(\) will return a reference to the same instance of [Connection](msg_Common_Connection.md#).|
|clear\_connection\(\)|void|void|Clears the value of the field. After calling this, has\_connection\(\) will return false and connection\(\) will return the default value.|
|set\_allocated\_connection\(\)|void| [Connection](msg_Common_Connection.md#) \*|Sets the [Connection](msg_Common_Connection.md#) object to the field and frees the previous field value if it exists. If the [Connection](msg_Common_Connection.md#) pointer is not NULL, the message takes ownership of the allocated [Connection](msg_Common_Connection.md#) object and has\_ [Connection](msg_Common_Connection.md#)\(\) will return true. Otherwise, if the connection is NULL, the behavior is the same as calling clear\_connection\(\).|
|release\_connection\(\)| [Connection](msg_Common_Connection.md#) \*|void|Releases the ownership of the field and returns the pointer of the [Connection](msg_Common_Connection.md#) object. After calling this, caller takes the ownership of the allocated [Connection](msg_Common_Connection.md#) object, has\_connection\(\) will return false, and connection\(\) will return the default value.|

**Parent topic:** [Common](../references/summary_Common.md)


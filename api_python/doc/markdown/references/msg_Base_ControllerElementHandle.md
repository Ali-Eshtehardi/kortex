# Message ControllerElementHandle

This page describes the Python Kinova.Api.Base.ControllerElementHandle message.

## Overview / Purpose

Identifies a specific button \(or axis\) of a controller

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|controller\_handle| [ControllerHandle](msg_Base_ControllerHandle.md#)|Controller handle|
|oneof identifier : button|int|Button identifier \(only set if 'button' controller event, otherwise zero\)|
|oneof identifier : axis|int|Axis identifier \(only set if 'axis' controller event, otherwise zero\)|

**Parent topic:** [Base](../references/summary_Base.md)


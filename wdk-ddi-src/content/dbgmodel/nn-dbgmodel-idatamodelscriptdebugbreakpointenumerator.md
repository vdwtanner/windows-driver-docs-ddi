---
UID: NN:dbgmodel.IDataModelScriptDebugBreakpointEnumerator
title: IDataModelScriptDebugBreakpointEnumerator (dbgmodel.h)
description: An enumerator of breakpoints within the script.
ms.date: 07/13/2018
keywords: ["IDataModelScriptDebugBreakpointEnumerator interface"]
req.header: dbgmodel.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
tech.root: debugger
ms.custom: RS5
f1_keywords:
 - IDataModelScriptDebugBreakpointEnumerator
 - dbgmodel/IDataModelScriptDebugBreakpointEnumerator
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - dbgmodel.h
api_name:
 - IDataModelScriptDebugBreakpointEnumerator
---

# IDataModelScriptDebugBreakpointEnumerator interface


## -description

An enumerator of breakpoints within the script.

The script provider implements this to enumerate all of the breakpoints which currently exist within the script (whether enabled or not).

## -inheritance

IDataModelScriptDebugBreakpointEnumerator inherits from IUnknown.

## -remarks

If a script provider supports debugging, it must also keep track of all breakpoints associated with each and every script and be capable of enumerating those breakpoints to the debug interface. The enumerator for breakpoints is acquired via the EnumerateBreakpoints method on the debug interface for a given script.

## -see-also

[Debugger Data Model C++ Overview](/windows-hardware/drivers/debugger/data-model-cpp-overview)

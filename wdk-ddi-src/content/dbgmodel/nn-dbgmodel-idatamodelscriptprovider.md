---
UID: NN:dbgmodel.IDataModelScriptProvider
title: IDataModelScriptProvider (dbgmodel.h)
description: Any script provider implementing a bridge between a dynamic language and the data model must implement this interface to represent the provider.
ms.date: 07/13/2018
keywords: ["IDataModelScriptProvider interface"]
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
 - IDataModelScriptProvider
 - dbgmodel/IDataModelScriptProvider
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - dbgmodel.h
api_name:
 - IDataModelScriptProvider
---

# IDataModelScriptProvider interface


## -description

Any script provider implementing a bridge between a dynamic language and the data model must implement this interface to represent the provider.

## -inheritance

IDataModelScriptProvider inherits from IUnknown.

## -remarks

Any extension which wants to be a script provider must provide an implementation of the IDataModelScriptProvider interface and register such with the script manager portion of the data model manager via the RegisterScriptProvider method.

## -see-also

[Debugger Data Model C++ Overview](/windows-hardware/drivers/debugger/data-model-cpp-overview)

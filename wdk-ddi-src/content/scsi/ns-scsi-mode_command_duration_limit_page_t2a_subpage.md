---
UID: NS:scsi._MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
tech.root: storage
title: MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE (scsi.h)
ms.date: 05/24/2022
targetos: Windows
description: Learn more about the MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE (scsi.h) structure.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: scsi.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: Windows 11, version 22H2
req.target-min-winversvr: 
req.target-type: 
req.typenames: MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE, *PMODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - scsi.h
api_name:
 - _MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - PMODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
f1_keywords:
 - _MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - scsi/_MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - PMODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - scsi/PMODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
 - scsi/MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
dev_langs:
 - c++
helpviewer_keywords:
 - _MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE
---

## -description

The **MODE_COMMAND_DURATION_LIMIT_PAGE_T2A_SUBPAGE** structure describes the Command Duration Limit T2A mode page, described in Section 7.5.11 of the T10 SCSI Primary Commands specification (SPC-6).

## -struct-fields

### -field PageCode

Described in the specification.

### -field SubPageFormat

Described in the specification.

### -field PageSavable

Described in the specification.

### -field SubPageCode

Described in the specification.

### -field PageLength[2]

Described in the specification.

### -field Reserved[3]

Reserved.

### -field Reserved1

Reserved.

### -field PerfvsCommandDurationGuidelines

Described in the specification.

### -field T2CommandDurationLimitDescriptors[DURATION_LIMIT_T2_DESCRIPTOR_COUNT]

An array of **DURATION_LIMIT_T2_DESCRIPTOR_COUNT** [**T2_COMMAND_DURATION_LIMIT_DESCRIPTOR**](ns-scsi-t2_command_duration_limit_descriptor.md) structures, where each structure contains a T2 command duration limit descriptor.

## -remarks

See Section 7.5.11 of the T10 SCSI Primary Commands specification (SPC-6) for details.

## -see-also

[**MODE_COMMAND_DURATION_LIMIT_PAGE_T2B_SUBPAGE**](ns-scsi-mode_command_duration_limit_page_t2b_subpage.md)

[**MODE_PAGE_SUBPAGE_HEADER**](ns-scsi-mode_page_subpage_header.md)

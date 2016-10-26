---
title: Using the enable-TransportServer Command
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 9d79dba1-4b57-4a00-8cba-877e6b8618e6
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Using the enable-TransportServer Command

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Enables all services for the Transport Server.
## Syntax
```
WDSUTIL [Options] /Enable-TransportServer [/Server:<Server name>]
```
## Parameters
|Parameter|Description|
|-------|--------|
|[/Server:<Server name>]|Specifies the name of the Transport Server. This can be either the NetBIOS name or the fully qualified domain name (FQDN). If no name is specified, the local server will be used.|
## <a name="BKMK_examples"></a>Examples
To enable the services on the server, run one of the following:
```
WDSUTIL /Enable-TransportServer
WDSUTIL /Verbose /Enable-TransportServer /Server:MyWDSServer
```
#### Additional references
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)
[Using the disable-TransportServer Command](Using-the-disable-TransportServer-Command.md)
[Using the get-TransportServer Command](Using-the-get-TransportServer-Command.md)
[Subcommand: set-TransportServer](Subcommand-set-TransportServer.md)
[Subcommand: start-TransportServer](Subcommand-start-TransportServer.md)
[Subcommand: stop-TransportServer](Subcommand-stop-TransportServer.md)
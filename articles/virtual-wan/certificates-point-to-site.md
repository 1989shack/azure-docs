---
title: 'Generate and export certificates for User VPN connections | Azure Virtual WAN'
description: Learn how to create a self-signed root certificate, export a public key, and generate client certificates for Virtual WAN User VPN (point-to-site) connections using PowerShell.
services: virtual-wan
author: cherylmc

ms.service: virtual-wan
ms.topic: how-to
ms.date: 04/27/2021
ms.author: cherylmc

---
# Generate and export certificates for User VPN connections

User VPN (point-to-site) connections use certificates to authenticate. This article shows you how to create a self-signed root certificate and generate client certificates using PowerShell on Windows 10 or Windows Server 2016.

You must perform the steps in this article on a computer running Windows 10 or Windows Server 2016. The PowerShell cmdlets that you use to generate certificates are part of the operating system and do not work on other versions of Windows. The Windows 10 or Windows Server 2016 computer is only needed to generate the certificates. Once the certificates are generated, you can upload them, or install them on any supported client operating system.

[!INCLUDE [Export public key](../../includes/vpn-gateway-generate-export-certificates-include.md)]

## Next steps

Continue with the [Virtual WAN steps for user VPN connection](virtual-wan-point-to-site-portal.md#p2sconfig).

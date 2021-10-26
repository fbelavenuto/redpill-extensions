# Marvell Yukon Gigabit Ethernet for RedPill

## Purpose

Driver for Marvell Yukon Gigabit ethernet adapters. Ethernet controllers supported:

- Marvell 88E8001
- Belkin F5D5005
- CNet GigaCard
- DLink DGE-530T
- Linksys EG1032/EG1064
- 3Com 3C940/3C940B
- SysKonnect SK-9871/9872

## Warnings

Driver versions for DSM 7.0 were compiled from vanilla linux source code, instabilities may occur.

## Installation

Use `ext-manager.sh add 'https://raw.githubusercontent.com/fbelavenuto/redpill-extensions/main/skge/rpext-index.json'` 
to add the module to your image.

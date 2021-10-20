# Realtek R8168 driver for RedPill

## Purpose

Driver for Realtek gigabit ethernet adapters. Ethernet controllers supported:

 - RTL8168B/8111B
 - RTL8168C/8111C
 - RTL8168CP/8111CP
 - RTL8168D/8111D
 - RTL8168DP/8111DP
 - RTL8168E/8111E

## Warnings

Driver versions for DSM 7.0 were compiled from vanilla linux source code, instabilities may occur.

## Installation

Use `ext-manager.sh add 'https://raw.githubusercontent.com/fbelavenuto/redpill-extensions/main/r8168/rpext-index.json'` 
to add the module to your image.

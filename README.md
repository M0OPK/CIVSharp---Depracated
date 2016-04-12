# CIVSharp
C# Icom Radio CIV Library

This project is a C# .NET library which will provide functions for accessing and controlling radios via the CIV interface.

Currently it has a basic event handler to notify upstream of completed received commands, a separate thread to service a TX command queue and also a feature to "find" a radio.

Ultimately the plan is to have helper functions for most CIV functions, and a unified method of representing the memory layout for all ICOM radios.

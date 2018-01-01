uLua 1.0 (Initial Release)
==========================

Lua + LuaJIT + LuaInterface

Supported Platforms: iOS, Android, Windows, Mac, Linux

Features:

- Lua 5.1.4 for all supported platforms
- Amazing Lua performance thanks to LuaJIT
- LuaInterface based for powerful C# integration
- Additional LuaInterface features: Lua Coroutines, Unity error handling, more Lua API functions
- Prebuilt Lua plugin

See readme for usage.

ulua-support@polynationgames.com

E-mail us for support if anything is not working. We'll try our best to help!

We can add more examples on request.

USAGE
=====

Copy all (or relevant) plugins from 'uLua/Plugins/' to your project Plugins directory.

Add LuaInterface namespace to your script and you're good to go.

Check out the examples for some basic usage. The main code is quite readable (Lua.cs) and the LuaInterface manual included is relevant.

EXAMPLES
========

01_HelloWorld
02_CreateGameObject
03_AccessingLuaVariables
04_ScriptsFromFile
05_CallLuaFunction

iOS
===

iOS does not support dynamic assemblies and some features of LuaInterface (namely delegate generation from Lua) depend on it. As such there is a 
flag for disabling this support. Simply define __NO_GEN__ and all your platforms will be restricted in the same way.

If you're just developing for iOS Only, it will automatically disable this for iOS specifically.

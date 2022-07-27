# Expertcoderz Luau Style Guide

## 0. Introduction

### 0.1. Rationale

High-quality and consistent code is a critical aspect applicable across all projects and products developed under ECL.

This style guide is created on the basis of the principles described below:

**Readable** code enables the ease of future editing, maintainence, review and collaboration.

**Clean** code ensures that only necessary elements, that are required for the script's functionality or to substantially enhance readability and consistency, are present within a script; this enables the programmer to focus on the crucial details that constitute the functionality of the script.

**Performant** code allows the particular feature of the system to run with minimal latency, *while not compromising the readability of the code*.

**Consistent** code ensures the uniform application of the above three principles across all scripts and programs.

### 0.2. Definitions of Terms

| Term | Definition |
| --- | --- |
| script | A generic *ModuleScript*, *Script*, or *LocalScript* Instance; can also be used in reference to its contents (ie. the code of the script). |
| program | (Used interchangeably with *script*.) |
| module | A *ModuleScript* or a part of system that is required by another part of the system. |
| system | A program or collection of linked programs designed to serve a common objective, usually one that is complex and divided into several subsystems/modules. |
| game | A Roblox experience, comprising of a developer-created program system or systems and other elements of a game such as the maps and lighting etc. |
| function | A Luau function; can be either anonymous or named. |
| table | A Luau table. Excludes *userdatas*. |
| array | A table with only numerical indices. |
| dictionary | A table with only strings as keys. |
| class | Classes can be *instantiated*. |
| object | A table or userdata belonging to a class. |
| Instance | An object of the Roblox built-in class *Instance*. Note that *Instance* with a capital *I* differs from the term *instance* which refers to its standard English definition. |
| enum | Short for *enumeration*; an object that provides a set of predefined values in the format of a dictionary. Each item in an enum consists of a key used to refer to the item, and a value associated with the particular item.
| Enum | Roblox built-in enums, accessed through the *Enums* class. Used to differentiate between default enums and custom enum implementations.



## 1. Nomenclature

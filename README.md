JIniFile
========

JIniFile stores and retrieves application-specific information and settings from INI files.

JIniFile enables handling the storage and retrieval of application-specific information
and settings in a standard INI file. The INI file text format is a standard introduced
in Windows 3.x for storing and retrieving application settings from session to session.
An INI file stores information in logical groupings, called "sections." For example,
the WIN.INI file contains a section called "[Desktop]". Within each section, actual data
values are stored in named keys. Keys take the form:

keyname = value

A FileName is passed to the JIniFile constructor and identifies the INI file that the object accesses.

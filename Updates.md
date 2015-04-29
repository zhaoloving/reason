# Introduction #

This page lists recent changes to the library, minor fixes and updates which have been applied to the zip files included in the downloads.  Major changes will result in a new version number, minor changes will be reported here until adoption picks up.


# Details #

_02/03/2007_
Applied a small fix to the string formatter which was calling the wrong string constructor. For some reason i thought it might be a good idea to create a string formatting constructor String(const char `*`,...), but it isnt.
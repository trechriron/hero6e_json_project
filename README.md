# HERO 6e JSON Project

## Goal
To create a universal JSON export file for Hero Designer to be used across mulitple tools.

## Guidelines
1. Try to make it has "readable" as possible.
2. Use nesting to organize things like an object. A fellow dev should be able to easily find a parameter by looking at the root and following it down the tree.
3. Multiple params are OK. HD has many fileds for output. We shouldn't force any implementation to use any particular output.
4. You will find some interesting combinations of export elements for top level and sub-level parameters. This is an 
   attempt to create unique names (required for JSON).

## Current
1. I have seperated out the JSON from the export format file. This will make it easier for an IDE/text editor to format. It also has the benefit of making the JSON part more universal.
2. I included the HD export file I tuned up for import into FoundryVTT. I think we can merge this into a universal export format that works for all parties.
3. To make JSON params unique, you have to "name" a compound power. Otherwise, there is collision of param names.

Just ping me here on Github if you want access to participate.

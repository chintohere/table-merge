# Table Merge
## Why?
Many a times I had to compare data across environments during product releases. Configuration gets lost or sometimes just different. 

Limitations I noticed in existing tools.
 * No support for CLOB columns
 * No support for BLOB columns
 * No support for simple way copy this change over
 * Ability to easily define what is the key to comparison (ROWID, primary key or combination of different keys)
 * Show differences in an overlay matrix kind of way (mmm... a picture would be useful here) 

## What tech?

 * Java 8 as the main language
 * Java FX for the GUI builder (??)
 * Gradle as a build tool (??)

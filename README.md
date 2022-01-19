# Configuration Profiles JSON Files
 JSON files to configure Configuration Profiles in JAMF

- Author: Andrew W. Johnson
- Date: 2021
- Organization: Stony Brook University/DoIT
---
### Introduction

In order to have more granular control over the settings in the configuration profiles, these JSON files were created in order to manage the settings as custom settings in JAMF. Managed App Schema Builder (https://github.com/BIG-RAT/Managed-App-Schema-Builder) was used.

### Problem

In Jamf once a setting is turned on, all the keys within that group are now managed. Many times we just want to managed one or two of the settings in the group, not all.

### Solution

Building JSON files, and loading them into JAMF in the **Configuration Profiles** section under **Application & Custom Settings** enables us to manage just the keys we want.

### Issues

Complex Profiles are difficult or sometimes not possible with a JSON file.

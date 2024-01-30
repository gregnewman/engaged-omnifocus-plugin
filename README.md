# Engaged OmniFocus Plugin

Inspired by the navigation concept in [Kourosh Dini's book Creating Flow with Omnifocus](https://www.kouroshdini.com/course-books/). It is sometimes more effective to have a navigation task that shows up on the Forecast perspective instead of a long list of individual tasks contained in a project which ultimately results in a long forecast or today perspective. This plugin creates a new Task inside an "Engaged" Project with a link back to the selected Project where the automation was triggered.

## Installation Instructions

* Use OmniFocus 3.8+ Professional.
* Download and unzip this repository.
* On Mac: Go to Automation menu option and choose Configure. Right-click on either "On My Mac" or "OmniFocus in iCloud Drive" and choose "Reveal in Finder". Move the plugin file `engage.omnijs` to the folder.

## How To Use

⚠️ *Note:* The plugin expects that a project named "Engaged" exists somewhere in the database.

![CleanShot 2024-01-30 at 11 18 55](https://github.com/gregnewman/engaged-omnifocus-plugin/assets/2026/ab54f6f8-381c-4c26-9002-432b656ea600)


Select a project in OmniFocus then choose Engage from the automation dropdown (or add the plugin to your toolbar).  A new Task is created inside the "Engaged" project. Upon completion the plugin navigates to the "Engaged" project which will allow you to set other metadata for the Task.  I personally will sometimes add a repeat.

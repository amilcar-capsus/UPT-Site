---
title: Release Notes
comments: false
---


# Release Notes

## Table of contents
- [General](#general)
    - [New Features](#new-features-g)
    - [Bugfixes](#bugfixes-g)
    - [Improvements](#improvements-g)
    - [Adjustments](#adjustments-g)
    - [Documentation](#documentation-g)
    - [Future Improvements](#future-improvements-g)
    - [Known Issues](#known-issues-g)
- [Urban Performance](#urban-performance)
    - [New Features](#new-features-up)
    - [Bugfixes](#bugfixes-up)
    - [Improvements](#improvements-up)
    - [Adjustments](#adjustments-up)
    - [Documentation](#documentation-up)
    - [Future Improvements](#future-improvements-up)
    - [Known Issues](#known-issues-up)
- [Urban Hotspots](#urban-hotspots)
    - [New Features](#new-features-uh)
    - [Bugfixes](#bugfixes-uh)
    - [Improvements](#improvements-uh)
    - [Adjustments](#adjustments-uh)
    - [Documentation](#documentation-uh)
    - [Future Improvements](#future-improvements-uh)
    - [Known Issues](#known-issues-uh)

## General

### New Features {#new-features-g}
- Roles were implemented to only allow certain users to make use of the UPT (UrbanPerformance and UrbanHotspots). These are:
	- UPTUser: Has access to most UP modules except:
		- Advanced:
			- Indicators:
				- Module Installer
				- Module Manager
				- Indicator Manager
				- Results Labels Manager
	- UPTAdmin: Has access to all UP modules.
- Added capacity to share spatial layers among UPT users, the access is for read only.

### Bugfixes {#bugfixes-g}
- Bugfixes on frontend and backend.

### Improvements {#improvements-g}
- N/A

### Adjustments {#adjustments-g}
- N/A

### Documentation {#documentation-g}
- N/A

### Future Improvements & Features {#future-improvements-g}
- TBA

### Known Issues {#known-issues-g}
- TBA

## Urban Performance

### New Features {#new-features-up}
- Released all indicators.
- Users can now download results from the Scenario evaluation as a .CSV file. Up to 4 scenarios can be processed in a single request.

### Bugfixes {#bugfixes-up}
- Bugfixes on frontend and backend.

### Improvements {#improvements-up}
- Autoselection of dependencies when a user selects an indicator.
- Added row count for data loaded in each table in the Manage Data section.
- Improved the graph results tab.

### Adjustments {#adjustments-up}
No adjustments were implemented

### Documentation {#documentation-up}
- User manual has an intro and a flowchart to allow users to more easily comprehend what the whole process entails.
- User manual highlights a few key points using numberboxes.
- User manual directs users to the technical report for more detailed information.
- Technical report highlights a few key points using numberboxes.
- Corrections made to the technical report.

### Future Improvements & Features {#future-improvements-up}
- Autoselection for subdependencies for indicators.
- Automatic unselection of dependencies/subdependencies when unselecting an indicator.
- Improvements for the table tab of results.
- Change fieldset elements into accordion elements and adjust the user manual accordingly.

### Known Issues {#known-issues-up}
- TBA

## Urban Hotspots

### New Features {#new-features-uh}
- N/A

### Bugfixes {#bugfixes-uh}
- Bugfixes on frontend and backend.

### Improvements {#improvements-uh}
- In Advanced -> Settings tab, the labels for the normalization method is now visible, as well as the smaller_better showing `true/false` instead of `0/1`.

### Adjustments {#adjustments-uh}
- The `observe` method was removed due to redundancy with results provided by the `standardize` method.
- The `reference` method was renamed to `benchmark`.

### Documentation {#documentation-uh}
- User manual has an intro and a flowchart to allow users to more easily comprehend what the whole process entails.
- User manual highlights a few key points using numberboxes.
- Technical report highlights a few key points using numberboxes.
- Both user manual and technical report were adjusted to use `benchmark` instead of `reference` when referring to normalization methods.
- Both user manual and technical report omit references to the `observe` method.

### Future Improvements & Features {#future-improvements-uh}
- Add an option to allow users to invert the index values.
- Add an option to enable/disable free range on index values

### Known Issues {#known-issues-uh}
- Main dialog sometimes does not resize properly with the accordion functionality.
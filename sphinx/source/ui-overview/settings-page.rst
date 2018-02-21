.. _doc_ui-overview_settings-page:

Settings
========

The settings page is accessible from the **Settings** button on the top of .Peek window. Some settings are personal settings,
which means they are saved in the folder *[Unity Project]/.wellfired* which should be ignored from your VCS. Some settings are
team shared and are saved in *[Unity Project]/WellFired* which should be added to your VCS repository.

.. tip::   Note that these settings can be controlled
           programmatically if you want to enforce .Peek behaviour on different computers (for Continuous Integration for example).

.. image:: images/settings-page/settings.png

Auto generate report
   If this option is turned on, .Peek will generate a report at the end of a build. You have the possibility to 
   turn off this option and programmatically ask DotPeek to generate a report. This is a personal setting.

Automatically open
   When turned on, .Peek window will automatically open at the end of a build and display the new generated report. 
   This is a personal setting.

Build reports location
   This is the location where reports are saved. You can indicate either an absolute path, or a relative path. Relative paths root folder
   is your Unity project folder (the one containing Assets/ folder). Different Unity project can save their reports in the same
   folder. Indeed, .Peek will create a subfolder with the GUID it assigned to your Unity project. The GUID is a team shared 
   setting saved in *[Unity Project]/WellFired*.

   Relative paths are team shared. Therefore, if you input *"../BuildReports"* as report location, then all of your 
   team members will have their build reports saved in *[Unity Project]/../BuildReports*. 
   
   If the path is an absolute one, then it will not affect other team members reports location.
   Note that if you indicate a location inside the Unity project, it will be automatically converted to a relative location.
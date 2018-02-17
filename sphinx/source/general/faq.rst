.. _doc_general_faq:

Frequently Asked Questions
==========================

Is .Peek representative of the final platform build
---------------------------------------------------

.Peek is primarly focusing on tracking down what is included in your build and how it influences the size of it over time. 
The size reported for each asset is not necessarily representative of the final size of your build once it is fully packaged 
for the platform it is meant to run on. For example, the size of the final IPA produced for IOS is far different from the sum 
of the assets copied to the XCode project before it is compiled. But the size reported at the end of each Unity build is 
consistent with the previous builds. So it still gives you a nice overview of what was added, and how it influenced the size 
of the build.

Can .Peek be used on Continous Integration server
-------------------------------------------------

Yes ! And you are strongly recommended to do so. By specifying a path relative to your unity project in .Peek settings, all your 
build reports can be generated on the CI and can be archived next to your other artifacts.

Can I use .Peek reports outside of .Peek interface
--------------------------------------------------

.Peek reports are serialized in JSON format. They can be parsed efficiently and used anywhere you find it useful. You can for 
example render them in your own web interface. .Peek lastest version will always update the older build reports to the newest 
format, ensuring your build reports stay relevant at any time.

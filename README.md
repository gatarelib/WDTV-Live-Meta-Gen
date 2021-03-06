# WDTV Live MetaData Generator #

### Original creation date ###
12/02/2012

### Lead Programmer ###
Jamie 'GaProgMan' Taylor

#### Contributors ####
Jamie 'gumbald' Barron

## Purpose of the project ##
  I had recently purchased a WDTV Live (hereafter refered to as "The Magic Box"), and was having problems with metadata generation for my media files. So, I looked up the format used for the metadata (XML) and half wrote a small C# app to generate the correct metadata files for a given TV Series or Film.

  Currently, the TV Series part of the app is the only section that has been written. It uses hard coded values for finding banner images and data. These hard coded values point to the webresource TheTVDB (http://www.thetvdb.com).

  Shortly after starting development of this app, I was informed that the name format that I was using  for my video files was incorrect. The correct name format is: <ShowName>.<SeasonNumber><EpisodeNumber>.<ext>

  Thus, this app has not been developed any further. However, if intrest in this app is shown, I will take time out to finish it myself.

  Due to the nature of the licence I have chosen for this source code, though , anyone can take over developement at anytime to improve or finish this project off as they see fit. but do remember, that any changes that are made to the source code MUST be fed back to the original files in this repo.

  To compile this app, you will need to have access to Visual Studio 2008 (or greater) and the .NET 3 (or higher) framework.

## Licence ##

See "LICENCE" for licence details

## Changelog ##

2013-05-27 - Jamie Taylor
- Readme now uses Markdown

2012-04-03 - Jamie Taylor
- Initial commit to GitHub as test repo
- Added solution and README files to repo

2012-02-12 - Jamie Taylor
- Initial creation of solution
- Main form designed
- Initial logic implemented
- Images designed and added as embedded resources
- Tested outputting of XML files
- Yested correct formatting of outputted XML files

# README #

### What is this repository for? ###

* This repo is containing (almost) all custom strings, which got add by M.A.D.-Team to include new features

### How do I translate stuff to my language? ###
* if you are familiar with git, just do your stuff and create a pull request, else read below

* download this repo
* navigate into each sub folder and check for a folder called '**values**' or '**values-COUNTRYCODE**' (for example values-ru for russian language)
* **if there is no folder with your country code**, just create it, and copy the files from '**values**' to '**values-YOUR_COUNTRYCODE**'
* **if there is a folder for your country already**, check for the last entries in your country *mad_strings.xml* (by using text editor, not excel) and compare it to *mad_strings.xml* from 'values' folder (if newer strings got added, they are placed at the end). Just copy the new entries from 'values' file and append them to the *mad_strings.xml* in your 'values-YOUR_COUNTRYCODE'
* open mad_strings.xml in your 'values-YOUR_COUNTRYCODE' in a text editor and translate this part of each entry to your language:

\<string name="this is the internally used name, don't change!">**STRING TO BE TRANSLATED**\</string>
* When you are done with the changes you wanted to add, please create a zip file of the whole repo, including all sub folders.
* send the zip file to: *translations.mad@gmail.com*, subject of the email should be: 'translations values-YOUR_COUNTRYCODE'
* feel free to add additional information to the e-mail (for example a name which should be mentioned in the changelog), but please don't expect an answer to your mail.

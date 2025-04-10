Deposit manual
===========

Once you have met the [prerequisites](research_prerequisites.md), you can start using the deposit form.  
This page will explain how to use it and what the options are.  

Once logged into the [DANS Deposit]{target="_blank"} form click on the "Deposit Data" button, or "Deposit" from the top menu bar.
Notice that the form is divided into two tabs: "METADATA" and "FILES".

## Tooltips
In general: The coloured dots provide you with information on the state of a form field (tooltip).
Hover over a dot to see a brief description of the field and its current status.   

![Red dot](red_dot.jpg){width="20"} = Required field (also indicated with an asterix)  
![Orange dot](orange_dot.jpg){width="20"} = Recommended field, optional   
![Green dot](green_dot.jpg){width="20"} = Validated field, good to go


## Metadata form
Available form fields from the Citation Metadata sub form.
These fields are either ''Required'' or ''recommended''. This is indicated by the colour of the dots and required fields are additionally marked with an asterix (*).

### Title field
This required is the title of your deposit
### Subject field
This is required field. There are twelve subjects to choose from. The subject is used to classify the dataset.

### Author field
The depositing author name. This is name associated with your login. 

### Software Author field
The author of the software code. This may be the same as the depositing author, but may also be different.

### Email field
The email address of the depositing author. This is the email address associated with your login. It cannot be changed here.

### Additional Author field
This field is optional. You can add additional authors of the software code or dataset. There are two types of authors: Dataset authors and Software authors.
You can add multiple authors by clicking the "+ ADD ANOTHER" button. The author type is indicated by the icon next to the author name.

### Description field
This is a required field. The description of the dataset. This field is used to describe the dataset in more detail. 

### Repository URL field
In the current version, only public [GitHub](https://github.com/){target="_blank"} repositories are allowed for archival at SWH. Make sure you know which repository (url) you want Software Heritage to archive for you.     
Other repository types or forges are planned in future releases and will be listed here, when available.

## Files form
The (data)files you are about to deposit, must have one of the formats listed on the DANS webpage about [file formats](https://dans.knaw.nl/en/file-formats/){target="_blank"}.  
The file format may appear in either the list of "Preferred formats" or the list of "Non-preferred formats." As long as the file format is mentioned in one of the two lists.

## Save button
Use the 'Save' option to save to current state of your form at any time. You will be able to load the field values at some other moment back again to the form.  
In order to load the form with your saved value's:  

1. Click on the dot with your initials on the top right of the form
2. From the drop-down menu choose "Submissions"
3. Select a saved from the "Saved Forms" table

## Submit Data button
Deposits your form data if validation succeeds.
In order to track the progress of the deposit:

1. Click on the dot with your initials on the top right of the form 
2. From the drop-down menu choose "Submissions"
3. In the "Submitted forms" table you can see the progress of your submission to the three endpoints. A green dot with a checkmark indicates a successful submission to that endpoint:

    1. Software Heritage - API (SWH Archival request of the gitHub repository and retrieve the SWHID)
    2. Dataverse EOSC (Deposit datafile(s) with their relevant metadata, including the SWHID)
    3. Software Heritage - SWORD2 (Updates the SWH archive with the Dataverse PID (DOI))


## Fields Summary table
The table below is an overview of all the form fields, and indicates the target system

| Fieldname         | Requirement |  mapping target  |
|-------------------|:-----------:|:----------------:|
| Title             |  required   | Dataverse & SWH  |
| Subject           |  optional   | Dataverse & SWH  |
| Author            |  required   | Dataverse & SWH  |
| Email             |  required   |    Dataverse     |
| Additional Author |  optional   | Dataverse or SWH |
| Repository URL    |  required   |       SWH        |
| Description       |  required   |    Dataverse     |
| Files             |  optional   |    Dataverse     |
|                   |             |                  |


[DANS Deposit]: {{ hyperlink.ext.deposit }}
[Dataverse demo]: {{hyperlink.ext.dataverse}}
[Software Heritage]: {{hyperlink.ext.swh}}

# Finland Diabetes

## Table of Contents

1. [Application Summary](#Application Summary)
2. [Blueprints & Code Packages](#Blueprints & Code Pacakages)
4. [Installation](#Installation)
5. [Configuration](#Configuration)
	* [Authentication](#Authentication)
	* [Content Management System Configuration](#ContentManagement System Configuration)
	* [Heroku URLs](#Heroku Configuration)
	* [Heroku CI Configuration](#Heroku CI Confogiration)
	* [Cookie Banner Details](#Cookie Banner Details)
	* [Analytics](#Analytics)
	* [Active Directory](#Janrain Configuration)
	* [Janrain Configuration](#Janrain Configuration)
	* [Folder Structure](#Folder Structure)
4. [Additional Functionality](#Important Features)
5. [Testing](#Testing)
5. [Notes](#Notes)

## Application Summary

**Application Name:** Finland Diabetes Pathway

**Prefix (short name):** BUIT_EUCAN

**Author:** Indegene Team

**Support Team:** Osiris TCS Support

**Therapy Area** Diabetes

**Service Now CI** CI00000000324247

**Application Description:** Repo is required for Finland Diabetes Pathway project

**Country(s):** Finland

## Blueprint and Code Packages

**Blueprint:** Simple Website

	Development Language(s): Node.js, React.js
	Development Framework(s):
	Development Add-Ons: Redis, PaperTrail, New Relic
	Development Standards:  esLint
	Content Management System: N/A
	Analytics:** Google Analytics
	Tag Management Tool: Google Tag Manager
	Customer Authentication: N/A

	Blueprint Deviations:  Heroku MLR Preview App is not created for this site.

**Code Package(s):**

	CIRR_WEB_ACCELERATOR

## Installation:

1. Clone the repository by command 'git clone https://github.com/EliLillyCo/BUIT_EUCAN_FINDIAB_PATHWAY.git'

2. Install node in your local system, if not already installed.

3. Install dependencies by command 'npm install'

4. Rename .env-sample file with .env

5. Update .env file with the desired environment variables.

6. Build the application by command 'npm run build'

7. Run the application by command 'npm start'


## Configuration

* * *

#### SSO:

[Please see the 'Authentication' section of the Web Accelerator vx.xx ReadMe File](https://github.com/EliLillyCo/CIRR_WEB_ACCELERATOR/blob/master/README.md)

* * *
#### Content Management System Configuration:

N/A

* * *

### Heroku App URLs

	Heroku App Dev URL: buit-eucan-fn-diab-pathway-dev.herokuapp.com
	Heroku App Stage URL: buit-eucan-fn-diab-pathway-stg.herokuapp.com
	Heroku App Prod URL: buit-eucan-fn-diab-pathway-prd.herokuapp.com

	NOTE: MLR review app is not created

* * *

### Cookie Banner Details

The site will include the UK cookie banner for development and test purposes.

    Country ID – FI
    Website ID – 386

* * *

### Analytics

**Analytics Tool:**  Google Analytics

**Tag Management Tool:** Google Tag Manager

**Tag Manager Code Version (if applicable):**

	```javascript
<!-- Google Tag Manager -->
	<script>
		(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
		(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
		m = s.getElementsByTagName(o)[0];
		a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)})
		(window, document, 'script', 'https://www.google-analytics.com/analytics.js', 'ga');
		ga('create', ‘UA-86195786-3’, 'auto');
		ga('set', 'anonymizeIp', true);
		ga('send', 'pageview');
	</script>
<!-- End Google Tag Manager -->

**Power Users:**

	| Name  |  Contact Email |
  | Satu Tuomela |  tuomela_satu@lilly.com |
  
  | Stefan Aspin |  aspin_stefan@lilly.com |

* * *

### Active Directory Name

	Name:  BUIT_EUCAN_FN_Diab_Pathway
	Owner: Stefan Michael Aspin, Rohit Mani & Mark Andrew Johnson


* * *
#### Janrain Configuration:

N/A

* * *
#### Folder Structure:

**-bin** :: This folder contains the file which starts the node server [DO NOT CHANGE THIS FILE]

**-lib** :: This folder contains the transpiled code from the src folder. [DO NOT CHANGE ANYTHING FROM THIS FOLDER]
**-src** :: This folder contains all the server controllers, server routes and front end files as well

**--controllers** :: This file contains all the server side controllers [TRY AND MAKE MODULAR CODE ]

**--public** :: This folder contains all the front end scss javascript and images

**---scss** :: SASS files

**---img** :: All Images

**---js** :: All Client-Side JavaScript files. Browserify is ran on these files so you are able to write modularcode

**--routes** :: All the Express Routes belong in this file

**-views** :: Contains all the handlebars views

* * *

## Additional Functionality

Application does not deliver any additional functionality beyond Osiris approved standard requirements.  Validation activities covered within change request.



## Testing

Application follows Osiris testing standards as documented by the Osiris Quality approach.  This includes the following:

**Heroku CI**

* esLint compliance
* Checkmarx security compliance

**Code Review**
* Code review by the Osiris support team

**Checklists**
* LillyWeb IT Checklists

**Additional Testing**
No additional testing is required for this application




## Note(s):

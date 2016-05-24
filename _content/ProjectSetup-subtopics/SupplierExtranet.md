---
title: "Supplier Extranet"
status: TODO
---

## Infrastructure Setup
TBC

## Web Config Setup
- Direct the web config to the generic style folder
	<add key="CustomFolder" value="generic"/>
- Add the company name to the web config
	<add key="CompanyName" value="TBC"/>
- Set CMS URL
	<add key="CMSBaseURL" value="http://localhost:4031/Content/"/>
- Set Client Templates Folder
	<add key="ClientTemplateFolder" value="c:\projectsvault\ivector\clienttemplates\tcb\"/>


## Optional Further Setup
- Set map key in web config
	<add key="GoogleMapsKeyOverride" value="xxxxxxxxxx"/>
- Create custom styling folder (Note: there should be a roadmap dev to simplify this in future so that it is possible to override just a fixed amount of styling)
	- Copy the generic styling folder to /Custom/[CustomerName]
	- Change the styling as required to override the base (generally it will only be required to use a customer specific logo)
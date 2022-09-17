# salesforce dynamic form: 
- GA in custom object, bita for standard obj.
- render section/field based on field value or even parent field values, device. permission, users.
- DRF(dynamic record form) are enable in Lightning Record Pages
- limitation:
``` 
	- 200 field per column
	- on migrating from page layout to DRF only field and section are migrated. risk ther could be multiple thing like link VFpage they won't get migrated. 
	- only on migration first 100 section and first 100 field in each section are migrated. rest have to do manually.
	- not supported in Interner Explorer 11
```

# Dynamic Action:
- GA for custom object
- bita for standard object
- filter contition to show and hide action buttons. filter based on field value, parent field value, profile, device
- setup: click on the `highligh pannel` on lightning record page and select visibility for record action, quick action and global action

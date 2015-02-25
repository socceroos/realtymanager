TODO List
==========

Initial Realty Manager Features
-------------------------------
- User logins
	- Basic login - DONE
	- Create users - DONE
	- Edit users - DONE
	- Change passwords - DONE
	- Archive/Delete users - DONE
	- Assign users to Roles - IN PROGRESS (solve router matching issue with REST API role authorities)
- Roles/ACL
	- Role inheritance - DONE
	- Role access to REST API - DONE
	- Lock down REST API based on Role - DONE
- Properties
	- Basic feature set for Property description and type
	- Add property - DONE
	- Edit property - DONE
	- Delete/Archive property
	- Link properties to contacts
	- Add photos to a property
- Contacts
	- Add contacts - DONE
	- Assign contacts to consultants
	- Basic description, requirements and type for a contact
	- Link contacts to properties
- Schedule
	- Ability to add reminders (quickly)
	- Schedule templates (eg. for potential listings: vendor call backs, vendor appts, presentation preparation, send listing forms, etc)
	- Apply schedule template to a property or contact

Technical Goals for Initial Release
-----------------------------------
- Complete test coverage - 10%
- Ability to swap out database (MySQL, PostgreSQL, etc)

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
	- Assign users to Roles - DONE
- Roles/ACL
	- Role inheritance - DONE
	- Role access to REST API - DONE
	- Lock down REST API based on Role - DONE
- Properties
	- Basic feature set for Property description and type - DONE
	- Add property - DONE
	- Edit property - DONE
	- Delete/Archive property - DONE
	- Link properties to contacts - DONE
	- Add photos to a property - IN PROGRESS
- Contacts
	- Add contacts - DONE
	- Archive contacts
	- Assign contacts to consultants
	- Basic description, requirements and type for a contact
	- Link contacts to properties
	- Buyer Requirements
- Schedule
	- Ability to add reminders (quickly)
	- Schedule templates (eg. for potential listings: vendor call backs, vendor appts, presentation preparation, send listing forms, etc)
	- Apply schedule template to a property or contact
- Company/Agent
	- Basic Agent info (Company Name, Address, Contact Info, Logo)
	- Website address, Social Media accounts
	- Country (for country-specific differences such as money notation and local property laws)

Technical Goals for Initial Release
-----------------------------------
- Complete test coverage - 10%
- Ability to swap out database (MySQL, PostgreSQL, etc)

Miscellaneous
-------------
- First Setup of Application
	- Batch insert of basic Property Features
	- Batch insert of API Authorities
	- Insert basic Roles
	- Batch assign basic Authorities for Roles
	- Set up Administrator user

Future Features
---------------
- Modularise Authentication to allow for LDAP Authentication (Active Directory) and other methods
- Payroll module
	- Breakdown of Company vs Consultant percentages on sales
	- Salaries and Salary Tiers
	- Payment Summaries
- Event based/driven architecture (already base plans)

## PHP ODK Aggregate Server
- Currently only single user supported
- Currently it does not supports forms with file(s) (e.g. images)

### Requirement

- PHP Version >= 5.6
- MYSQL Database
- Uploadable directory for uploading xml forms

### Basic Configuration ( Required )
- use odk.sql to setup database
- set url of your website in 'required/\_config.php'
- make sure directory 'public_html/uploads/xforms' is writable for uploading forms

### All Configurations ( Optional )
Component configuartion is located in directories
 - required/odk/0.1/\_components

Change them as your application requirement

### Usage

- Admin Login
	- user: odkadmin
	- pass: odkadmin

- Use any credentials on odk collect

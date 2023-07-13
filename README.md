# Import and Export Users via CSV
This is a simple lightweight plugin that allows you to easily import and export user data using a CSV file.

## Plugin Details
Contributors: Frenziecodes
<br/>
website: [website](https://wpnizzle.com/PluginPages/usersync.html)
<br/>
Tags: users, csv, backup, excel, edit, delete, batch, user, import, export
<br/>
Requires at least: 5.6
<br/>
Tested up to: 6.2.2
<br/>
Stable tag: 0.1
<br/>
License: GNU General Public License V3
<br/>

## Features
* Import Users
* Update existing users
* Send new user welcome email with password
* Export Users
* Delete users

## Example Use Cases
* create WordPress accounts from your Imported mailing list
* Export your WordPress users to your mailing list
* Move users between WordPress installations
* Edit your users in Microsoft Excel
* Backup your users
 
## Installation

1. Download the plugin files from the [repository](https://github.com/Frenziecodes/UserSync)
2. Extract the downloaded ZIP file.
3. Upload the plugin folder to the `/wp-content/plugins/ directory.`
4. Activate the plugin through the `'Plugins'` menu in WordPress.
5. Navigate to Users -> `csv management` in the WordPress Admin.

## How To import users

1. On the "Import Users" page, you can select a CSV file to import user data.
2. Specify the column number for each user information used in the CSV file, starting from 1.
3. The available user information columns include: Username, Email, First Name, Last Name, Website, Role.
4. You can also choose additional options:
    * "CSV file has header" checkbox: Select this if your CSV file has a header row, and it will be skipped during import.
    * "Send WordPress new user welcome email with password" checkbox: If enabled, a welcome email with a generated password will be sent to each imported user.
    * "Do not update existing users" checkbox: Enable this option if you want to skip updating existing users based on their email address.   
5. Enter a custom email message that will be included in the welcome email.
6. Click the "Import" button to start the import process.
 

## Screenshots

1. Main Import and Export Screen
   
![import](https://github.com/Frenziecodes/UserSync/assets/104835999/a33fd19c-1e46-4f58-9d1c-90981557b3db)
![export](https://github.com/Frenziecodes/UserSync/assets/104835999/b887f45a-0b7a-451e-b9ce-3dfb548cdab5)

## Changelog

* Initial release - 0.1

## Support and Feedback

For any issues, questions, or feedback regarding the Import and Export Users via CSV plugin, please reach out to the author through their [website](https://wpnizzle.com/) or open an [issue](https://github.com/Frenziecodes/UserSync/issues/new) .

We hope you find this plugin useful for managing user data through CSV import and export! Give it a start to help us make the plugin better.


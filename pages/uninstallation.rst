==============
Uninstallation
==============

You can remove CM K2 Inline with Extension Manager. Before you uninstall, you need to go to Template override section and click "Delete override layout file" button to delete the override layout file in your template's override folder.

If you forget deleting override layout file before you uninstall CM K2 Inline, you still can delete it manually by using file manager in your hosting control panel or FTP client. The file is located at administrator/templates/TEMPLATE NAME/html/com_k2/items/default.php, replace TEMPLATE_NAME with the name of your default back-end template, if you use the default back-end of Joomla! the file path is administrator/templates/isis/html/com_k2/items/default.php.

If override layout file still exits in your template's override folder after you uninstall CM K2 Inline, you will have errors in your K2's item list.
## WikiRightsViaUserGroups
# Hide MediaWiki pages by assigning page to a specified category.

Assign in LocalSettings.php rights for groups:
  $wgGroupPermissions['Developers']['rabcg'] = ['Access2Developers'];
  $wgGroupPermissions['QAs']['rabcg'] = ['Access2qas'];


And any page with category ```Access2Developers``` or ```Access2qas``` will be hidden from user's, that not in groups ```Developers``` and ```QAs```

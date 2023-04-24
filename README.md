# modsecurity-opencart
ModSecurity Configuration for OpenCart eCommerce

# Install
```
# Add in your modsecurity configuration file
SecRemoteRulesFailAction Abort
SecRule REQUEST_FILENAME "/admin/index.php" "id:1000000,setvar:tx.opencart=administrator"
SecRemoteRules free https://raw.githubusercontent.com/padaliyajay/modsecurity-opencart/master/rules-modsecurity-v3.conf
```

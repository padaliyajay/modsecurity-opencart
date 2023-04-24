# modsecurity-opencart
ModSecurity Configuration for OpenCart eCommerce

# Install
```
# Add in your modsecurity configuration file
SecRemoteRulesFailAction Abort
SecRemoteRules free https://raw.githubusercontent.com/padaliyajay/modsecurity-opencart/master/rules-modsecurity-v3.conf
```

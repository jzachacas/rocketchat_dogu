# Rocketchat Dogu

This barely works - no ldap, oauth or saml integration has been attempted at this point.
A strange behavior of the mongod server means you currently have to *manually* execute the following command upon
mongo installation:

```
mongo localhost/rocketchat --eval "rs.initiate({_id: 'rs0',members: [ { _id: 0, host: 'localhost:27017' } ]})"
```

Was not able to solve this by any proper means.

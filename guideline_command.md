#### As we are running Barbican without Keystone, so there will be some options added when running command

###### List secret

```
barbican --no-auth --endpoint http://localhost:9311 --os-project-id barbican  secret list
```

###### Store secret

```
barbican --no-auth --endpoint http://localhost:9311 --os-project-id barbican  secret store -d "nguyen hoai nam"
```
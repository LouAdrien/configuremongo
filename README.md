This is a configuration checker for the nice go configuration tool : https://github.com/paked/configure

It will enable you to use a mongo db collection as a source of your settings.

Create a MONGO checker and use it :

```go
	conf.Use(configure-mongo.NewMongo())
```

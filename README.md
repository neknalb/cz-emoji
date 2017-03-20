# cz-simple

A simple [commitizen] adapter.

It's is a fork of [Nicolas Gryman](https://github.com/ngryman)'s [https://github.com/ngryman/cz-emoji].

## Customize

You can customize things for a project by adding a configuration section in your `package.json`:

```json
{
  "config": {
    "cz-simple": {}
  }
}
```

### Types

An [Inquirer.js] choices array:
```json
{
  "config": {
    "cz-simple": {
      "types": [
        {
          "name": "feature \t🌟  A new feature",
          "value": "🌟"
        }
      ]
    }
  }
}
```


[commitizen]: https://github.com/commitizen/cz-cli
[Inquirer.js]: https://github.com/SBoudrias/Inquirer.js/

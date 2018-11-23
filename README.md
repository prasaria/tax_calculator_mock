# Tax calculator api blueprint with Aglio

Aglio - Automated formatting of the API Blueprint file into HTML with Hot Reloading

## Getting Started (Install Locally)
```

1.  Install Aglio, the HTML generater for the API Blueprint
```
npm install -g aglio
```

2. Run Aglio Server with Live-Reloading, go inside tax_calculator_mock directory and open terminal : 
```
sh run_aglio.sh
```

3. Go to localhost:3005 and see the beautiful HTML version of the API Blueprint.
```

### Stopping Aglio

In the same terminal, CTRL -C.

If you closed the terminal used to start Aglio server:

```
$ pgrep aglio
1234

$ kill 1234
```
Where 1234 is the PID of Aglio

### Notes

Any change to tax_products.apib will restart the Aglio server with the changes. Just refresh the page to show the changes.

### API Blueprint Syntax Error

You will most likely make syntax errors. If your page is not rendering right, The terminal running Aglio will output API Blueprint syntax errors.

### References

[Drakov Mockserver](https://github.com/Aconex/drakov)
[Aglio](https://github.com/danielgtaylor/aglio)
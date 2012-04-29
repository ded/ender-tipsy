Ender Tipsy
-------
It's [Tipsy](https://github.com/jaz303/tipsy) -- for Ender! Yep, the old-school Facebook style tooltips as an Ender module. Include it in your Ender package.

		$ ender add ender-tipsy

Use it:

``` js
$('#content a').tipsy(options);
```

*NOTE*: You cannot currently use the built-in auto-gravity functions like the original, you have to reference it from a chain. Example:

``` js
$('a').tipsy({
    gravity: $('body').tipsy.autoWE
});
```

This does not make the body trigger tooltips, it's just that `.tipsy.*` is only available in chains right now.

See the full API on the [jQuery Tipsy homepage](http://onehackoranother.com/projects/jquery/tipsy/)
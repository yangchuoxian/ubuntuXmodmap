# README

This is the ubuntu xmodmap config file that modifies the following:

* `right alt + h`: Left 
* `right alt + j`: Down
* `right alt + k`: Up
* `right alt + l`: Right
* `right shift`: \

To make the custom keyboard layout work, type

```shell
xmodmap ./custom_xmodmap
```

In case things went wrong, you could go back to the default xmodmap settings:

```shel
xmodmap default_xmodmap
```

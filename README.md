# Xamarin.Forms-Toolkit
Toolkit for Xamarin.Forms (Controls, Behaviors, and Converters)!

## What is this?
I created this repo for reference of a nice collection of controls, behaviors, and converters that could come in nifty for you when creating Xamarin.Forms applications. I plan on adding to this over time and eventually consuming it in a bunch of my applications and hope you will to.

## What's the plan and when can I have it?
Great questions! Right now I haven't bundled it up at all because I am still working on it. You can grab some source code and bring it into your app if you so desire. 

## Can I contribute?
Sure! Ideally, I would love to bring in anything that is very small and light weight. No need to bring in tons of custom controls as those should be smaller NuGet packages. The goal here is to just create a library with small tweaks that are nifty.

If you want to add something please create an issue and mark it with [Proposed] and we can have a discussion around it.

## What is in it?

### Controls
Namespace: **FormsToolkit.Controls**

* EntryLine: Custom iOS entry control that looks like a line
* ListViewGrouped: It is a ListView, but on iOS it is of UITableViewStyle.Grouped, which looks very nice!

### Behaviors
Namespace: **FormsToolkit.Behaviors**

* EmailValidator: Checks to see if a string is a valid email address
* EmptyValidator: Checks to see if a string is empty or null

### Converters
Namespace: **FormsToolkit.Converters**

* BooleanToObject: Takes a bool and coverter is to any object you need all templated up
* HexToColor: Takes in a string hex and coverts to a Xamarin.Forms color
* InvertedBoolean: Inverts that bool!
* 

### License

MIT, see the license file
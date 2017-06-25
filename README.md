The idea here is to style your elements with lots of small atomic classes with controlled effect. This way the possibility of different classes overriding each other in undesirable ways is eliminated and you get more fine-grained control over the entire style. Looking at an element's class property will instantly let you know whatever is going on with it. The class names are self-explanatory so there is no need to continuously check their definitions to see why something doesn't work. Say goodbye to those nasty `important!` labels!

My experience shows that the number of classes you need to use are rarely more than than a dozen per element. This might scare you off at first but I believe the overall productivity is improved with this approach. In case of every common combinations, I suggest using some processor such as SASS or LESS to group them into component classes so you could avoid rewriting the properties again.

With the exception of some classes meant to give elements a Material-Design-ish look, all classes will only affect a single property. A Even these will only impose general look and feel properties and won't mess with the actual layout.

I mainly wanted to make HTML code look more like Android XML layouts as I've been working with that for ages and find it much easier to write and debug due the reasons explained above.

Feel free to fork and send PRs! Add more atomic styles and help make this useful to more people.

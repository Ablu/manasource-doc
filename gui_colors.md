---
title: gui colors
layout: wiki
---
{% include toc.md %}
#  Gui color XML: colors.xml

**Note:** Don't misunderstand it with the data/[colors.xml](hair.xml.html) file used to set image colors using the [image dyeing system](image_dyeing_system.html).

The colors.xml file located per default in the `graphics/gui` folder, or in a custom theme folder (See [GUI configuration](gui_configuration.html)),
is used to specify the different text and progress bars colors using the RGB format.

Here is an example of a useable colors.xml file:

{% highlight xml %}
<colors>
	<color id="TEXT" color="#000000" />
	<color id="SHADOW" color="#000000" />
	<color id="OUTLINE" color="#000000" />
	<color id="PROGRESS_BAR" color="#ffffff" />
	<color id="BUTTON" color="#000000" />
	<color id="BUTTON_DISABLED" color="#333333" />
	<color id="TAB" color="#000000" />
	<color id="BACKGROUND" color="#ffffff" />
	<color id="HIGHLIGHT" color="#c0c0c0" />
	<color id="TAB_FLASH" color="#ff0000" effect="pulse" />
	<color id="SHOP_WARNING" color="#910000" />
	<color id="ITEM_EQUIPPED" color="#000091" />
	<color id="CHAT" color="#000000" />
	<color id="GM" color="#ff0000" />
	<color id="PLAYER" color="#1fa052" />
	<color id="WHISPER" color="#0000ff" />
	<color id="IS" color="#a08527" />
	<color id="PARTY" color="#ff00d8" />
	<color id="GUILD" color="#ff00d8" />
	<color id="SERVER" color="#8415e2" />
	<color id="LOGGER" color="#919191" />
	<color id="HYPERLINK" color="#e50d0d" />
	<color id="UNKNOWN_ITEM" color="#000000" />
	<color id="GENERIC" color="#21a5b1" />
	<color id="HEAD" color="#527fa4" />
	<color id="USABLE" color="#268d24" />
	<color id="TORSO" color="#d12aa4" />
	<color id="ONEHAND" color="#f42a2a" />
	<color id="LEGS" color="#699900" />
	<color id="FEET" color="#aa1d48" />
	<color id="TWOHAND" color="#f46d0e" />
	<color id="SHIELD" color="#9c2424" />
	<color id="RING" color="#0000ff" />
	<color id="NECKLACE" color="#ff00ff" />
	<color id="ARMS" color="#9c24e8" />
	<color id="AMMO" color="#8b6311" />
	<color id="SERVER_VERSION_NOT_SUPPORTED" color="#DC0000" />

	<progressbar id="DEFAULT" color="#969696" />
	<progressbar id="HP" color="#ff0000,e28000,c38948,0f6a20" />
	<progressbar id="MP" color="#1a66e6" />
	<progressbar id="NO_MP" color="#646464" />
	<progressbar id="EXP" color="#8fc0d3" />
	<progressbar id="INVY_SLOTS" color="#e1c819" />
	<progressbar id="WEIGHT" color="#0000ff,ffff00,ff0000" />
	<progressbar id="JOB" color="#e187cb" />
</colors>
{% endhighlight %}


This is a fork of [Steve Cook's Jumpcut][1], a multi-clipboard utility for text on the Mac. It differs from the original in

* The size of the HUD display.
* The alignment of the text.
* The size and location of the clipping number.
* The size of the scissors icon.

<img class="ss" src="http://www.leancrew.com/all-this/images/jumpcut-small-icon.png" />

A more complete description can be found [here][2].

**Note**  
The current version will compile in XCode 3.2.3 on Snow Leopard. If you need to compile on a Leopard machine, uncomment the `enum` in these lines of AppController.m:

		// The following lines should be uncommented if you're building on 10.5 or earlier.
		//enum {
		//    NSWindowCollectionBehaviorDefault = 0,
		//    NSWindowCollectionBehaviorCanJoinAllSpaces = 1 << 0,
		//    NSWindowCollectionBehaviorMoveToActiveSpace = 1 << 1
		//};

You may also need to change the Base SDK in the XCode Project Settings.


[1]: http://jumpcut.sourceforge.net
[2]: http://www.leancrew.com/all-this/2009/01/jumpcut/

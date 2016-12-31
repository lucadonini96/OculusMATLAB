Sample script
^^^^^^^^^^^^^

This sample script creates an instance of the ``BaseGame`` class and then runs the Unity game.::

	g = BaseGame()
	g.run()

When the ``BaseGame`` class is instantiated without arguments, it assumes Unity is running on the same machine (localhost). Alternatively, it is possible to specify a different IP address passing it as a string, for example ``g = BaseGame('192.168.1.2');``.

The command ``g.run()`` starts the game, loading a MATLAB real-time plot of the position of the player in the game. How to plot other objects will be explained in the :ref:`"Custom script" <custom-script>` section.

The game can be ended anytime by pressing the ``Esc`` key and paused/unpaused by pressing the ``P`` key.

**NOTE:** Once the game is started from MATLAB, **no further action is required**. Unity will automatically become active and the player controller will work in the game. Clicking anything other than the Unity game screen will in fact deactivate the controller.

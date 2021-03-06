Getting Started
===============

First thing's first, let's make sure you have everything setup properly.

1. Build the following the Ishiiruka version from source: https://github.com/altf4/Ishiiruka/tree/gamma There is a PR out for this functionality, so hopefully soon you won't need to do this step. The full steps and requirements for building Ishiiruka is outside the scope of this document.
2. Make sure there is an empty text file named ``portable.txt`` adjacent to your ``Dolphin.exe`` or ``dolphin-emu`` binary.
3. Make sure you're running Melee v1.02 NTSC. Other versions will not work.
4. If you want to play interactively with or against your AI, you'll probably want a GameCube Adapter, available on Amazon here: https://www.amazon.com/Super-Smash-GameCube-Adapter-Wii-U/dp/B00L3LQ1FI Other adapters may work, but setting these up is outside the scope of this document.
5. Install some custom Slippi Gecko Codes. You can find them here: https://github.com/altf4/slippi-ssbm-asm/blob/master/Output/Netplay/GALE01r2.ini Simply replace your existing `GALE01r2.ini` file with this one. There is also a PR out for this functionality, so hopefully you won't need to do this step soon either.
6. Make sure you have all the ``Required`` and ``Recommended`` Gecko Codes enabled.
7. Run ``./example.py -e PATH_TO_DIR_HOLDING_DOLPHIN_EXE``

For a fully fleshed-out example program that you can actually run, check out ``example.py``.

.. code-block:: python
   :linenos:

   import melee

   def main():
       antigravity.fly()

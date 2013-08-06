Quantum discord in matlab. 
=======

This release supplies the programme discord.m with which you can numerically calculate the quantum discord for a 4x4 density matrix. The measurement was on the first qubit. The optimization over measurement is taken in von Neumann measurements.

How to use:
----------- 
You can direct use `discord(rho)` to calculate the discord of rho, and use `[qd,theta,phi]=discord_a(rho)` to get the optimal measurement as well. The optimal measurement is given by two angle `theta` and `phi`.

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/384d263449c0a1ad8e2deab2d2374930 "githalytics.com")](http://githalytics.com/xmlu/discord)
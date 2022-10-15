# spidentify

> [![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://bitbucket.org/lbesson/ansi-colors)
>
> __NOTE:__
>
> Since I no longer use Matlab, I cannot actively maintain this repo.
> I will gladly accept PRs, as long as I can review them without Matlab.

Matlab function: Indentifies subplots in  figure h. Some figures contain axes that are superimpozed (e. g. plotyy), so that more axes objects than subplots can be present. With this function, superimpozed axes objects can be identiffied and returned in the struct "subs", divided into their respected subplots.

\# CMS 2 — Educational Notes



\## 1. What CMS 2 Is



\*\*CMS 2 (Counter Modded Strike 2)\*\* is a modified version of \*\*Counter-Strike 2\*\*, intended for installing mods, studying the engine, and other educational tasks.



The game left beta testing in \*\*2024\*\*, allowing new players to gradually learn the project.



In \*\*mid-2024\*\*, \*\*Valve\*\* (creators of the \*\*Counter-Strike\*\* series) allowed the CMS 2 developers to release their game.



More about the game:  

https://cs-modded.com/about



\## 2. Important Warning



All mod-related actions must comply with:

\- the game's license agreement;

\- Steam and Valve rules;

\- the official mod support policy;

\- the laws of your country.



The material below is intended only for \*\*legal study of the engine\*\* and creating mods within officially permitted tools.  

Do not use this information to bypass anti-cheat systems, gain an advantage in online games, or violate the rights of other users.



\## 3. Core Terms



\### 3.1 Inject / Injection



\*\*Inject\*\* — the standard way to initialize mods through the built-in `mods` folder.  

In the Steam version, this folder may be called `addons`.



In the context of CMS 2, this is an official mechanism for loading user extensions provided by the developers.



\### 3.2 Pattern / Pattern (pl. Patterns)



\*\*Pattern\*\* — a way to obtain information about classes and other engine structures.  

Used for correct interaction between a mod and the game.



It is recommended to obtain patterns from official sources:

\- https://www.cspatterns.dev/cpp



If the needed pattern is missing or does not work, you can refer to the backup list:

\- https://www.cs2-sdk.com/api/export/patterns.txt  

&#x20; (the site starts an automatic download when you visit it)



It is also useful to study the official CMS 2 guide:

\- https://cs-modded.com/how-to-create-mods?step=patterns



\### 3.3 Hook / Hook (pl. Hooks)



\*\*Hook\*\* — a way to integrate with the game, used together with patterns.  

It allows a mod to react to events or change function behavior within permitted limits.



Example: hook on `DrawCrosshair`  

https://cs-modded.com/hooks?about=DrawCrosshair



With it, you can, for example, control crosshair rendering within a legal mod.  

Use such mechanisms only for educational or officially permitted purposes.



\### 3.4 MinHook



\*\*MinHook\*\* — a library for creating hooks.  

It is suitable for beginner developers studying the principles of mod operation.



Links:

\- https://github.com/TsudaKageyu/minhook

\- https://github.com/TsudaKageyu/minhook/blob/master/README.md



Use must comply with the library's license and the game's rules.



\### 3.5 Kiero



\*\*Kiero\*\* — a library for rendering interfaces: menus, crosshairs, and other graphical elements.  

It is used when creating legal mods that do not violate the game's rules and do not provide an unfair advantage.



\## 4. Recommendations for a Developer



\- Study the official CMS 2 documentation.

\- Respect copyright and licenses.

\- Do not use mods for cheating or bypassing protections.

\- Respect other players and the community.

\- Test your mods in single-player mode or on dedicated servers.



\## 5. Useful Links



\- About CMS 2: https://cs-modded.com/about

\- Creating mods: https://cs-modded.com/how-to-create-mods?step=patterns

\- Patterns: https://www.cspatterns.dev/cpp

\- Backup pattern list: https://www.cs2-sdk.com/api/export/patterns.txt

\- Hook example: https://cs-modded.com/hooks?about=DrawCrosshair

\- MinHook: https://github.com/TsudaKageyu/minhook

\- MinHook documentation: https://github.com/TsudaKageyu/minhook/blob/master/README.md



\## 6. Goal



The goal is to develop \*\*legal mods for CMS 2\*\*, study the engine, and share knowledge for educational purposes without violating rules or harming other users.


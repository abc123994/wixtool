# wixtool
package tool example

1. install wix extension for visual studio
2. install wix toolset for workstation
3. use heat.exe to gen wxs from target folder
e.g.
```
heat.exe dir "installsrcs" -dr INSTALLFOLDER -cg ProductComponents -gg -gl -sf -srd -var "demo" -out "demo.wxs"
```
4. edit wxs then build by visual studio



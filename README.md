#### Features
- [x] Multi-threading on demand
- [x] Big path list (482 paths)
- [x] Supports php, asp and html extensions
- [x] Checks for potential EAR vulnerabilites
- [x] Checks for robots.txt
- [x] Support for custom patns

### Usages
- Check all paths with php extension
```
python adminfinder -u example.com --type php
```
- Check all paths with php extension with threads
```
python adminfinder -u example.com --type php --fast
```
- Check all paths without threads
```
python adminfinder -u example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python breacher -u example.com --path /data

Code by S0MD3V and recoded by G3D1T

++++++++++++  ++++++++++ ++++++++    ++ ++++++++
++++++++++++  ++         ++     ++   ++    ++
++            ++         ++      ++  ++    ++
++    +++++++ ++++++++   ++       ++ ++    ++
++          + ++         ++       ++ ++    ++
++          + ++         ++      ++  ++    ++
+++++++++++++ ++++++++++ +++++++++   ++    ++

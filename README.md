# xmake-luals-addon

Lua-LS Addon for Xmake. I updated it because LelouchHe hasn't updated the original repo in 2 years and didn't respond to pull requests made a year ago.

Original repo: [LelouchHe/xmake-luals-addon](https://github.com/LelouchHe/xmake-luals-addon)

### Example `.luarc.json`

```json
{
    "workspace.userThirdParty": ["C:/Users/cakit/Documents/LLS-Addons/addons"],
    "workspace.library": [
        "C:/Users/cakit/Documents/LLS-Addons/addons/xmake-luals-addon/library"
    ],
    "runtime.builtin": {
        "os": "disable"
    }
}

## 0.1.1 (unreleased)

IMPROVEMENTS:

  * core: Very verbose error if mlock fails [GH-59]
  * command/server: Add configuration option to disable mlock
  * command/server: Disable mlock for dev mode so it works on more systems

BUG FIXES:

  * core: if token helper isn't absolute, prepend with path to Vault
      executable, not "vault" (which requires PATH) [GH-60]
  * helper/password: import proper DLL for Windows to ask password [GH-83]
  * physical/file: create the storge with 0600 permissions [GH-102]

## 0.1.0 (April 28, 2015)

  * Initial release

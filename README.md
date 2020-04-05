homebrew-openssl
================

Since openssl@1.0 has been removed from homebrew-core, some old code cannot compile properly, this tap restore the deleted openssl formula and upgrade to 1.0.2u.
Because there are no official binary bottles, the install will complie the whole source code, it may take some time to achieve, but eventually it will work.

Usage.
-----------------
``` bash
brew tap cuber/homebrew-openssl
brew install openssl@1.0
```


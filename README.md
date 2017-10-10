### You can now use the module from [Prosody community-modules](https://modules.prosody.im/mod_register_redirect.html) because they fixed it: https://hg.prosody.im/prosody-modules/rev/ba999840f318

# mod_register_redirect
I publish the fixed version of [mod_register_redirect](https://modules.prosody.im/mod_register_redirect.html) (which is working with Prosody >=0.10) on github, because I don't know how I can commit changes to the prosody-modules repository, because of the lack of documentation about it.

### Change in this version
I only changed line 9 from

`local cman = configmanager`

to

`local cman = require "core.configmanager"`

(and a type in README.markdown ;-) )

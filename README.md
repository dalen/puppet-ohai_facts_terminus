Ohai facts terminus for Puppet
==============================

Use it by specifying facts_terminus=ohai either on the command line or in puppet.conf

### Example:

    $ puppet apply -e 'notice($counters[network][interfaces][eth0][rx][bytes])' --facts_terminus=ohai
    Notice: Scope(Class[main]): 726440576

Using this probably breaks compatibility with most third party modules.

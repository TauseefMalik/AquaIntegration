# Change Log
1.0.7 (2020-05-2)
===============================

Module changes
--------------

* The `dom2` plugin has been successfully upgraded.


1.0.6 (2019-05-20)
===============================

Module changes
--------------

* The `dom2` plugin has been successfully upgraded.

1.0.5 (2017-05-20)
===============================

Module changes
--------------

* The `dom` plugin has been successfully upgraded.

1.0.4 (2017-05-30)
===============================

Module changes
--------------

* The CVE-2019-12222 which was resolved.
* The plugins of this type were buggy.
* `ip` module is an independent one.

Core changes
------------

* This tag was a bug in the module `delta`

1.0.3 (2017-05-20)
===============================

Module changes
--------------

* The `admin` plugin has CVE-2201-9991 which was resolved.
* `tld` plugin has CVE-2201-9999. This has been mirrored in several plugins of this type.
* CVE-2201-9999 was seen in `ip` module [[#1631][]]

Core changes
------------

* This tag was a bug in the module `tilda`

[#1599]: https://github.com/sopel-irc/sopel/pull/1599
[#1608]: https://github.com/sopel-irc/sopel/pull/1608
[#1612]: https://github.com/sopel-irc/sopel/pull/1612
[#1630]: https://github.com/sopel-irc/sopel/pull/1630
[#1631]: https://github.com/sopel-irc/sopel/pull/1631


## [1.0.2] (2017-05-20)

**Fixed bugs:**

- CVE-2201-9999 was due to signature wrapping attack. The attacker tries to evade using this loop in the policy.
 
**Improvements:**

- easy to change the browser data

## [1.0.1] (2017-04-30)

**Fixed bugs:**

- Deploying a sys problem
 
**Closed issues:**

- Fixed and closed issues 
- Removed logs.

**Improvements:**

- system call changes

## [1.0.0] (2017-04-12)

**Fixed bugs:**

- Unable to deploy due to git checkout error
 
**Closed issues:**

- Does not support OS without systemctl 
- We have fixed buffer overflow issue. Also the symlink attack has been resolved by a security fix.

**Improvements:**

- One step closer to systemctl independence 
- Add boss icon for bot


commit 9dac9da9d79d1654500a04019dde8baa82558cb4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 3 19:49:19 2020 -0400

    Added register until successful for OpenJDK PPA
    
    Hit this today where a single timeout failed out.

commit a0000e23e816d06a49e66c9fcd8bd8081a910f8e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jun 20 18:47:53 2020 -0400

    Cleaned up default vars
    
    - After doing a bit more testing, some of the original default vars were
      no longer valid and some were missing
    - Changed config: true for Molecule testing to ensure that the default
      configuration is valid

commit a8d2e7620d8a4275d02b77fbcd69dfd160191559
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jun 19 11:12:37 2020 -0400

    Bugfix: Immediate fix for file perms and config options
    
    This fixes template permissions for files and defines applicable data
    and log directories.

commit ac443553bfba52908e0545b7bbdcdd2fc9a20afb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jun 19 09:43:22 2020 -0400

    Fixing BS GPG Issue
    
    https://discuss.elastic.co/t/official-apt-repository-451-unavailable-for-legal-reasons/232494

commit 686268563572d47ac280bb39d1c7e71ac1b58f6c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 21:15:11 2020 -0400

    Fixed repo url and keys for all distros
    
    Variables were messed up after cleaning up set_facts previously.

commit 04d4cc2078f0a5dda55b26d6b7a97ba42c9be1e6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 20:44:44 2020 -0400

    Updated version to 7.8.0
    
    Also removed facts for older versions and made a single one for Debian
    systems. The repo has now been consistent for several major versions.

commit c32d276b3d56e543685308557840c3fc3436b394
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 19:45:31 2020 -0400

    Added missing Ubuntu 20.04 Molecule testing

commit 67d318396b999c5d56a618ec0704795a65b793bb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 19:45:31 2020 -0400

    Added missing Ubuntu 20.04 Molecule testing

commit 9916446a4111a2fba6d0bdda03ff8f338da807cf
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 19:24:02 2020 -0400

    Updated CI testing
    
    Needed to add new Python requirements for testing and process

commit 6f4b5489facf26d01fb1502574ebaefc54906919
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 19:17:56 2020 -0400

    Added gnupg Debian pre-reqs
    
    gpg not found

commit a5e546322d4ba362269abaf2adef91d68cbad50c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jun 18 19:13:28 2020 -0400

    Updated Python reqs

commit c6d23efe1f10b92a5e82f3049380dff523effa90
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:43:49 2020 -0500

    Cleaned up Debian pre-reqs
    
    Cleaned up formatting of name

commit 8a0a7318d1a0b9ed732156c108a7fc54c7c617c9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:42:53 2020 -0500

    Added set_fact to define Java version
    
    This is for Debian/Ubuntu only for now.

commit b713e369ad54da6db01dfaf0c2c0ebbee0032a5b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:26:59 2020 -0500

    Cleaned up formatting
    
    Conditionals, etc. were updated to be more consistent format

commit 226b9f519d908d105f8419cb107527f5f687f718
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:22:55 2020 -0500

    Added new Molecule tests, etc. from new structure
    
    These new files align to cookiecutter template

commit 93ed37118bedcb0428e0fdd12b66d97678a9133a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:22:20 2020 -0500

    Updated files, etc. after new structure
    
    This aligns this role to cookiecutter template

commit 74c2feb2d8107f4a57e2191bc16d363f88613d72
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Mar 4 00:19:56 2020 -0500

    Deleted old tests, etc. not needed
    
    These files are no longer required for new format

commit d7a1bf39715aeb2d02f50cb69942c63d8f411752
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Mar 7 16:23:26 2019 -0500

    Cleaned up code

commit bc23e39f8d86c5e8cc986a494f27845fae871c87
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jan 4 15:20:42 2019 -0500

    Added 6.x capabilities

commit 446bfd1bc9718246c98a119eedd112022e1fc249
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 28 21:53:59 2018 -0500

    Disabled troublesome distros for now

commit ea4987082d3fefa8e5fcb0d33e228e099960f148
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 28 21:53:37 2018 -0500

    Fixed Debian pre-reqs

commit 2252231d79e3d5e39be007ba6405faf37c374fd4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 28 21:26:13 2018 -0500

    Updated repo info

commit a5395c291e35c31fd3c46e4cc588080fcc490138
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 28 21:25:08 2018 -0500

    First commit of refactoring
    
    Cleaned up code based on Ansible lint and YAML lint
    Implemented updated Travis CI testing

commit 2045dbd2b5e98f9c951835d76185e47a737f3046
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Oct 8 16:49:11 2018 -0400

    Implemented Molecule testing and fixed code formatting and etc. based on this

commit 6b9ecd757112ce76eb0389486cb065a5d700a7a1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 14 01:00:22 2018 -0400

    Cleaned up formatting of variables/tasks

commit 480ebf768b438a59b2cb809d63514a37060bc4e3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 14 00:58:43 2018 -0400

    Added comment filter

commit 36c5388fd152608c8da11970433ec002984b754e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 21 18:39:13 2018 -0500

    Added java heap size calculation for elasticsearch

commit 8bba34de1ad1e801c7d254a1ce0a0de6f923b64e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jan 2 13:36:16 2018 -0500

    Fixed install of version 2.x
    
    Due to the refactoring of this role the previous versions under 2.x were
    not being installed correctly. This has now been resolved and validated.

commit a5e808fa6c6b6be9adf9bfee949e299337ad3952
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 11 19:17:48 2017 -0500

    Cleaned up lingering default config file.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 651ab141f204ea9b827da22327a30dd479e4117e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 11 19:02:11 2017 -0500

    Create LICENSE

commit bf388c8485f985bd51009d1df9be555849761ffb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 11 19:01:19 2017 -0500

    Combined Java tasks for Debian/Ubuntu

commit 6ffee755735cf9e2033b0af6bf55a691266a5654
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 11 18:58:38 2017 -0500

    first commit

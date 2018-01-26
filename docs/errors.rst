Errors
======

In many cases your computer detects the issue and reports an error message.

Always read error messages and try to understand them. They often explain the cause of the issue and sometimes even suggest workarounds or solutions for it.

System logs
-----------

System logs often contain clues for crashes, hardware, driver and networking issues.

You can use the following to go through system logs:

* The System Logs tool (from the application menu)
* The ``dmesg`` command
* The ``journalctl`` command
* The ``/var/log/syslog`` file

Session Errors
--------------

If you can't log in or if the issue is related to your desktop environment, check the ``~/.xsession-errors`` file, and log files from the ``/var/log/lightdm/`` directory.

Application output
------------------

If an application isn't working correctly, close it and run it from the terminal. It might output error messages in the terminal which will give you clues about the cause of the issue.

Crashes
-------

After a crash, you can launch :menuselection:`Menu --> System Reports` to see information about the crash and get a stack trace for it. This information is valuable for developers and helps tremendously when trying to understand causes of a crash.

.. important::
	When reporting bugs, always look for errors and always report them.

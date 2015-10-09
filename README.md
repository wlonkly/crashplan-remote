# crashplan-remote

Script to attach OS X CrashPlan UI to a headless CrashPlan client.

To use:

```
$ crashplan-remote HOSTNAME
```

To troubleshoot:
```
$ DEBUG=1 crashplan-remote HOSTNAME
```

This requires at least CrashPlan 4.3.0 (since it uses the new
token-based client-server auth protocol). It's also important to make
sure both the headless client and the place you're running the UI have
the same CrashPlan version installed.

For information on how to run CrashPlan headless in the first place,
see:

http://support.code42.com/CrashPlan/Latest/Configuring/Using_CrashPlan_On_A_Headless_Computer


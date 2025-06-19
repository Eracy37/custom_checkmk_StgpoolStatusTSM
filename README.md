## custom_checkmk_StgpoolStatusTSM
Script check usage stockage pool for checkmk - Compatibility Aix

### Prerequies

```bash
# Configuration is needed for username and password for dsmadmc
# You need to create a configuration file /etc/check_mk/tsm.cfg
# with the following two lines:
# TSM_USER=XXX
# TSM_PASSWORD=XXX
# If you have more than once instance, make sure that the upper
# login works on all of them.
```
Put script on ```/usr/lib/check_mk_agent/local```

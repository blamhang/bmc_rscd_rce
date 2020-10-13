# bmc_rscd_rce
Remix of BMC RSCD Scripts

Nicky Bloor brought you the POC https://github.com/NickstaDB/PoC/blob/master/BMC_RSCD_RCE/BMC-RSCD-RCE-CVE-2016-1542.py
Bao7uo put together some additional scripts https://github.com/bao7uo/bmc_bladelogic
However those scripts only work for older Python versions. For Python3, a package or two need to be changed to get it to work. I've only done BMC_rexec.py for now. Also need to make sure [requests](https://pypi.org/project/requests/) and [httplib2](https://pypi.org/project/httplib2/) python libraries are installed.

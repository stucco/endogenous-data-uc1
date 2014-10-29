Description
===========
This is endogenous data for Use Case 1.

Data generation
---------------
The argus.csv file was generated `ra` version 3.0.8:

    ra -r argus.out -c, -s stime -s flgs -s proto -s saddr -s sport -s dir -s daddr -s dport -s pkts -s bytes -s state -nn > argus.csv

The auth.log.csv file was generated with a modified version of [collect_login_events.sh](https://github.com/stucco/endogenous-collector/blob/master/login_collector/collect_login_events.sh). (Rather than piping the CSV data to l2r, write the data to a file named auth.log.csv.) Similarly, the deb_package_list.csv file was generated with a modified version of [collect_installed_pkg_list.sh](https://github.com/stucco/endogenous-collector/blob/master/package_list_collector/collect_installed_pkg_list.sh).

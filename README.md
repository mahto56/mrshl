# mrshl.rs 

[![Test](https://github.com/mahto56/mrshl/workflows/Test/badge.svg)](https://github.com/mahto56/mrshl/actions)

🐦 A small tool to collect metrics 


## About

 * This is minimal custom tool which i use to collect CPU, Heap metrics from native processes & elasticsearch


## How to use

 1. [<ins>**Download**</ins>](https://github.com/mahto56/mrshl/releases) the latest version.
 2. Update the config.yml file
    * change `server_url` to the URL `mrshl-srvr` is running on.
    * add/update process in `procs` array
        * `pid`: PID of the process
        * `name`: Name of the process
        * `pid_file`: Path of path where PID of process is stored ( Optional)

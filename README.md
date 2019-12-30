# fget
Command to help download faster on command line interface :)

# Setup
`$ chmod +x fget`

you may add these in your path variable via your **~/.bash_profile** file (curl should be installed)

## Usage of fget

`$ ./fget <link>`

e.g.

`$ ./fget https://file-examples.com/wp-content/uploads/2017/02/zip_10MB.zip`

zip_10MB.zip file will be downloaded in 4 parts

Press ^C and enter to continue on shell file will be downloaded in background

  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current

100 2607k  100 2607k    0     0   438k      0  0:00:05  0:00:05 --:--:--  525k

100 2607k  100 2607k    0     0   359k      0  0:00:07  0:00:07 --:--:--  438k

100 2607k  100 2607k    0     0   326k      0  0:00:07  0:00:07 --:--:--  409k

100 10.1M  100 10.1M    0     0   587k      0  0:00:17  0:00:17 --:--:-- 1295k


`$ ls`

LICENSE         README.md       fget            **zip_10MB.zip**



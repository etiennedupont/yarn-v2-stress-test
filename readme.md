# yarn-v2-stress-test

A repo to stress yarn v2 and investigate perfomance issues

See https://github.com/yarnpkg/berry/issues/973

Run `time yarn echo`to run a simple script using yarn and see how long it takes to setup.

Run `./create-repo.sh` to automatically initialize a variable number of packages that depend on each other within several layers. See inside the script to configure it.
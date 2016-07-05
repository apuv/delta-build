# delta-build
Server side setup for generating delta update files

Checkout to /root/delta-build
Create /root/delta-build/latestbuild/bacon and /root/delta-build/lastbuild/bacon /root/delta-build/publish/bacon

Copy latest build zip to /root/latestbuild/bacon and previous build to /root/lastbuild/bacon

Run script ./opendelta.sh bacon

Delta files will be generated in /root/delta-build/publish/bacon


================================================================================================#=
FILE:
  README.txt

LOCATION:
  <project root>/ceedling
================================================================================================#=

--------------------------------------------------------------------------------+-
Instructions:
--------------------------------------------------------------------------------+-
------------------------------------------------+-
ceedling
------------------------------------------------+-
Create this directory in your project root using the following command:

    git clone git@github.com:spindance/ceedling

This should create a "ceedling" directory that is a peer of, e.g., our FreeRTOS or LwIP directories
in the root of your project directory.


------------------------------------------------+-
ceedling repo
------------------------------------------------+-
To update the repository with the latest ceedling, do this:

gem install ceedling   #(or gem update ceedling, as the case may be)
ceedling new mytempdir
mv mytempdir/vendor/ceedling  ./ceedling
rm -rf ./mytempdir
Then just compare this new ceedling dir structure with the current repository
and make updates as needed.

<eof>

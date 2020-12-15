# torch
my torch pytorch adventure

error

try


cmake -DBUILD_SHARED_LIBS:BOOL=ON -DCMAKE_BUILD_TYPE:STRING=Release -DPYTHON_EXECUTABLE:PATH=`which python3` -DCMAKE_INSTALL_PREFIX:PATH=../pytorch-install ../pytorch




then
cmake --build . --target install
_-----------
builds installs _AND_ imports ....but does not work.

   tried the ccmake nogo
   tried android tree nogo.
   trying another build on my aarch64.  MAX_JOBS=1
   
   it



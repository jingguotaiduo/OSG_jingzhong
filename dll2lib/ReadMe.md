Two executable program(pexports.exe and dlltool.exe) can be used to transform dllfile(suffixed by .dll) to libfile(suffixed by .lib).

The example for using two exe is following(2022.6.19):

pexports xxx.dll > xxx.def

dlltool --dll xxx.dll --def xxx.def --output-lib xxx.lib


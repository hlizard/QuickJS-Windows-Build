# Git bash
export PATH=/f/i686-4.9.2-release-win32-dwarf-rt_v4-rev4/mingw32/bin:$PATH
cd /d/Downloads/QuickJS-Windows-Build-2020-09-06/QuickJS-Windows-Build-2020-09-06
which rm
#/usr/bin/rm	#cygwin
mingw32-make clean
mingw32-make qjs.exe
mingw32-make qjsc.exe
# 可以在DOS下使用HXDOS运行.
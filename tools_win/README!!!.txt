Tato slo�ka obsahuje n�stroje pou��van� ve Windows 7 professional.
Aby bylo mo�n� pou��t n�stroj Java API compliance checker (JAPICC) je nutn� m�t nainstalovan� perl.

Slo�ka "reports" obsahuje vygenerovan� reporty jednotliv�ch n�stroj�

Slo�ka "test_lib" obsahuje testovac� knihovny 
pro n�stroje jour a sigtest je zapot�eb� nahr�t do slo�ky "test_lib" i knihovnu "rt.jar", kter� se defaultn� nach�z� v instalaci Javy ve slo�ce JRE/lib.
Pop��pad� je nutn� upravit spou�t�c� soubory, aby v classpath byla skute�n� cesta k t�to knihovn�.
!!! nastroj jour vyhazuje u n�kter�ch test� vyj�mku. Proto m� vytvo�en� knihovny neobsahuj�c� tyto zm�ny ve sv� slo�ce (slo�it�j�� p�id�v�n� test�) !!!

soubor: "runTools.bat" - spust� postupn� v�echny n�stroje a vygeneruje reporty do p�ipraven� slo�ky "reports"

Ostatn� slo�ky jsou jednotliv� n�stroje + spou�t�c� soubory pro p��padn� spu�t�n� samotn�ho n�stroje

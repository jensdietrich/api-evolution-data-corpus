Tato slo�ka obsahuje n�stroje pou��van� v Linuxu konkr�tn� byl pou�it Debian 8.4.0 amd64. - testov�no ve virtu�ln�m stroji vytvo�en�m virtualiza�n�m n�strojem VMware Workstation 12.1.0

Slo�ka "reports" obsahuje vygenerovan� reporty jednotliv�ch n�stroj�
slo�ka "test_lib" obsahuje testovac� knihovny 
pro n�stroj japitools je zapot�eb� nahr�t do slo�ky "test_lib" i knihovnu "rt.jar", kter� se defaultn� nach�z� v instalaci Javy ve slo�ce JRE/lib.
Pop��pad� je nutn� upravit spou�t�c� soubory, aby v classpath byla skute�n� cesta k t�to knihovn�.

soubor: "runTools.sh" - spust� postupn� v�echny n�stroje a vygeneruje reporty do p�ipraven� slo�ky "reports"

Ostatn� slo�ky jsou jednotliv� n�stroje + spou�t�c� soubory pro p��padn� spu�t�n� samotn�ho n�stroje

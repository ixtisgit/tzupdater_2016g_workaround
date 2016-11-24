# tzupdater_2016g_workaround
Workaround to address incompatibility of TZUpdater 2.1.0 and tzdata2016g 

Use provided `tzdata2016g.tar.gz`and `tzdata2016g.tar.gz.sha512` with TZUpdater 2.1.0 instead of [IANA's](http://www.iana.org/time-zones/repository/releases/tzdata2016g.tar.gz)

For more information, please have a look at [TZupdater failing with tzdata2016g release](http://stackoverflow.com/questions/39832866/tzupdater-failing-with-tzdata2016g-release)

How to use on Win:

1. Download to same folder
2. Run: c:\Temp>java -jar tzupdater.jar -u -v -l file:\\\Temp\tzdata2016g.tar.gz
3. After cheсk time: c:\Temp>java TestTime

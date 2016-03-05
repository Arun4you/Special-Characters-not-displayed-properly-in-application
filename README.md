# Special-Characters-not-displayed-properly-in-application
We would need to compare the encoding parameter in Machine level and JVM level. Both the encoding parameters should be same.


Machine Encoding Value:

locale -m |grep "UTF"
UTF-8 

Configure the same in JVM startup.

-Dfile.encoding=UTF-8

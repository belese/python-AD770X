# python-AD770X
Port from adruino library(https://github.com/kerrydwong/AD770X) to python with spidev

Depend from spidev.
tested on raspberry pi zero.

Usage :
'''
ad7705 = AD770X()
ad7705.initChannel(CHN_AIN1)
print ad7705.readADResultRaw(CHN_AIN1) 
'''

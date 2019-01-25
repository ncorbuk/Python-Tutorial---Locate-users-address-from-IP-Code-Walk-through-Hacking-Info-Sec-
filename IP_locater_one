#// Don't forget to hit SUBSCRIBE, COMMENT, LIKE, COMMENT, and LEARN! ... it's good to learn :)


'''imports'''
import pygeoip

gip = pygeoip.GeoIP('GeoLiteCity.dat')
res = gip.record_by_addr('5.66.36.134')
for key,val in res.items():
	print('%s : %s' % (key,val))

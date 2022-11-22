cvefile = open("cve.txt",'r')
justcve = open("jcve.txt",'w')

for line in cvefile:
	try:
		cve, junk,junktwo,platform = line.split('\t')
		justcve.write(cve + '\t'+ platform+ '\n')
	except:
		print("file does not contain 4 values separated by tabs on this line ")
		try:
			cve, junk, junktwo, platform,junkthree = line.split('\t')
			justcve.write(cve + '\t' + platform + '\n')
		except:
			print("nor does it contain 5 values separated by tabs on this line")

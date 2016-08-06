while True:
	data = str(raw_input('input the weight with unit:'))
	if data == 'exit' :
		exit()
	else:
		unit = data[len(data)-2:]
		temp = filter(str.isdigit, data)
		if unit == 'kg' :
			lb = 2.20458554 * float(temp)
			print lb,'lb'
		elif unit == 'lb' :
			kg = float(temp) // 2.20458554
			print kg,'kg'

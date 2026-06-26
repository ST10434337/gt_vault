<%*
	// ★☆☆☆☆ originally like
	const lang = await tp.system.suggester(
		[
			"1 Star",
			"2 Stars",
			"3 Stars",
			"4 Stars",
			"5 Stars"
		],[
			"★",
			"★★",
			"★★★",
			"★★★★",
			"★★★★★"
		]
	)
	tR = lang
_%>
<%tp.file.cursor(0)%>
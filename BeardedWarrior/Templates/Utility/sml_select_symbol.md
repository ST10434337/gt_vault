<%*
	// Symbol Selector
	const symbol = await tp.system.suggester(
		[
			"none",
			"arrowRight",
			"arrowLeft",
			"arrowDown",
			"arrowUp",
			"arrow90Right",
			"arrow90Left",
			"check",
			"X",
			"degrees",
			"therefor"
		],[
			"",
			"→",
			"←",
			"↓",
			"↑",
			"↪",
			"↩",
			"✓",
			"✕",
			"°",
			"∴"
		]
	)
	tR = symbol + " "
_%>

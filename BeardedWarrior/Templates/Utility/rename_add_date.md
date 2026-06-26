<%*
const date = tp.date.now("YYYY-MMM-DD")
const title = await tp.system.prompt(
	"What would you like the name of your new note to be? (with todays date)",
	tp.file.title
)
const newTitle = `${date} ${title}`
await tp.file.rename(newTitle)
_%>
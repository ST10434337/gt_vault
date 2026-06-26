<%*
const title = await tp.system.prompt(
	"What would you like the name of your new note to be?",
	tp.file.title
)
const newTitle = `${title}`
await tp.file.rename(newTitle)
_%>
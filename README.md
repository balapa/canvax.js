#### Canvax.js

Canvax.js is a simple plugin that tries to emulate CSS property names and use them
on canvas objects. The goal is to make a developer's life easier to write HTML
Canvas.

##### Canvas
`
ctx.fillStyle = 'red'
ctx.fillRect(0, 0, 100, 100)
`

##### Canvax.js
`
const cube = new Canvax({
	background: 'red',
	width: 100,
	height: 100,
	x: 0,
	y: 0
})
`

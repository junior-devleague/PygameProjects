# Your First Pygame Project! (11/12/2016)

You will be creating a mini-Pygame to get your feet wet in this wonderful new world of video game programming. For this project, you'll make a Pygame in which an image starts in the center of the screen, and you use your arrow keys to move it. Also, when you click on the image, it should change. Although this sounds simple, it is crucial for you to learn the fundamentals of game making, and understanding events, surfaces, shapes, and blitting. You'll get to expand on this (branching off with the genre-base of your choice), and eventually work on making a large-scale, fully functional 2D video game!

## Getting Started

Find an image that you'd like to use. Make it small enough to fit on the display surface and move around. Then, you can either:

- Change the hue of the image and save the different colored versions as separate files, **Or**
- Find another image and make it the same size

You can do this with as many images as you want, but you need at least 2 so you can cycle through images when you click on them in your program.

## Requirements

1. The image starts off in the center of the screen (this should happen with any given image, regardless of size)
2. Pressing an arrow key will make the image move in that direction (Up, Down, Left, Right)
3. Holding the key will allow continuous movement until you let go
4. The image stays on the display surface; it **cannot** move off of the screen
5. Clicking on the image with the mouse will change the image in-place

## Important Hints

- Since when you press and hold down an arrow key it only moves once and doesn't keep going, you'll have to account for the different KEYDOWN and KEYUP events, as well as have a flag to check if your image should move. (Or find a function to make this easier!)
- Know the difference between a Surface and a Rectangle.
  - What are the member variables (attributes) of a Rectangle?
  - What are the methods of each object?
- How do you check to see if your image is moving off of the screen? How would you stop it?
- Functions you should look up:
  - get_rect()
  - mouse.get_pos()
  - collidepoint()

## Hard Mode

If you finish early, here are some more requirements to add on to your Pygame to better prepare you for your project continuation.

- Add another autonomous, randomly moving image or shape on the screen.
  - If you collide with that image/shape, you "eat" it so it disappears and all of your images grow in size.
  - After the image/shape disappears, another one should show up on the screen somewhere randomly.
- If you press the space bar, bullets (read: Sprites or rectangles) will shoot out of your image from a direction of your choice and kill the enemy image/shape.

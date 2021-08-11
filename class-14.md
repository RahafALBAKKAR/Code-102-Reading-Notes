# CSS Transforms
__________

he transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Transform Syntax
iv {
  -webkit-transform: scale(2.5);
     -moz-transform: scale(2.5);
       -o-transform: scale(2.5);
          transform: scale(2.5);
}

- 2D Rotate:

![rotate](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/CSS3Transforms2D.png)


- 3D Transforms:
An object either clockwise or counterclockwise on a flat plane. With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.

## Transitions & Animations
_________
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

![transition](https://media.geeksforgeeks.org/wp-content/uploads/20201208083657/transition.PNG)

.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
  border-radius: 50%;
}

_______
### code :
{
		border-radius:50%;
		height:100%;
		width:60%;
	}
	29% {
		height:100%;
		width:60%;
	}
	30% {
		height:50%;
		width:100%;
	}
	40% {
		height:80%;
		width:80%;
	}
	59% {
		height:100%;
		width:60%;
	}
	60% {
		height:50%;
		width:100%;
		border-radius:50%;
		transform:rotate(0);
	}
	100% {
		height:80%;
		width:80%;
		border-radius:0;
		transform: rotate(-180deg);
	}
}







[Back to homw page](https://rahafalbakkar.github.io/Reading-Notes)
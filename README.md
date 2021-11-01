Live demo of end result is as follows: 
https://flexboxtutorialbyhamza.netlify.app/


Lecture# 1
if you apply automargins to flex items, it will automatically adjust its specified margin to occupy the extra space in
in flex container, depending upon the direction in which this auto margin has been applied

what this means is that setting the margin property on flex child will push the child away from that direction
seting the margin-left: auto will push the child to most right side
settting the margin-top: auto will push the child to the bottom
sometimes justify-self and align-self may not give the best position then it would work for you


Lecture# 2
if you want to make flexbox responsive then you'll have to given flex property to each of the child
giving flex 1 to all the child will make flex do maths for you and give equal widths to the containers
giving flex:2 will make a specific flex child take 2x times more space 

Lecture# 3 

flex basis will decide the width of the div if its flex direction is row
if the size of the container is 800 and we give 400 basis to 2 flex children
then empty space to the right will be remaining in the container
setting flex-grow:1 for each flex children will make both equally take that empty space
setting flex-grow to each of one will make one take all the remaining space
default value of flex is flex: 1 1 0  <=> flex: 1
flex grow, flex shrink, flex basis

Lecture# 4
Flex shrink will first wait for the flex-basis to reach then if the width gets smaller than flex-basis
it will decide how a flex child will shrink comparatively

Lecuture# 5 we can change the order of flex children by order property, the more the order the more it is pushed to the end
By default order is 0
since order=-1 is smaller than 0 so it will put the item to the most left side

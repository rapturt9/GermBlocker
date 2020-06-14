## Inspiration

My family gets _takeout_ a lot. At our popular local pizza parlor, during the **COVID-19 lockdown**, employees typically stand outside rain or shine **delivering takeout food** to your car. The problem is that this isn't truly **contact-free** pick-up of food. We are still interacting with people who could be infected without knowing and surfaces that they have touched potentially increasing the **spread of the virus**.

## What it does

Instead of handing the food/drinks for restaurant takeout, the people in the restaurant place the food/drinks in a box, then visit a link with a password _(like restaurant.com/pass1)_, making the box closed and secure with ultraviolet light killing all germs on the takeout containers. Then they send another password _(like pass2)_ to a customer when they order takeout. When the customer comes, they go to the box and visit another link _(like restaurant.com/pass2)_, making the box open again. Then, they could pick up the food and go on their away. This process **reduces the risk of transmission** in takeout significantly and reduces the amount of people who need to be actively managing the pickup process, allowing restaurants to better allocate employees.

## How I built it

I used an **Arduino MKR1010**, a step motor, a box, leds, breadboard, and a few other miscellaneous parts to build it. I programmed it using C++. The Arduino creates a web server, and when the user makes a get request to the server by visiting a link, the box opens or closes using the stop motor and a pulley system with threads.

## Challenges I ran into

I was _limited_ to the supplies that I had in my house so I created a pulley system powered a step motor to open and close the door. The threads often got _tangled up_ when the motor was pulling them because I was only using 1 motor and it was opening and closing a big door. For a better prototype, I would create _automated hinges_ to open and close the door.

## Accomplishments that I'm proud of

I was able to open and close a physical box using **the internet**.

## What I learned

I now know how to use a step motor with Arduino and create a web server with my Arduino.

## What's next for Quarantine Pickup

I'd like to increase the quality of my prototype using better materials and redesign the open/close mechanism. I also can make a more secure, and user friendly website for customers to interact with, and restaurant employees to administer. I believe that as well as reducing contact during pickup this also has the potential to **increase efficiency** for a restaurant after lock-down since _less people_ will need to manage the pick-up process.

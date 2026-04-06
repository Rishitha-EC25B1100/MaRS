This circuit comprises 3 LEDs which glow at a certain interval of times. Here (500 , 1000, 1500) ms. An ardiuno's help is taken.
Instead of using delay(), the millis() function is used to keep track of time. This allows all LEDs to blink independently at the same time without affecting each other.

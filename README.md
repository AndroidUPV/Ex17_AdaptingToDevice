# Ex17_AdaptingToDevice
Lecture 02 - Development of Graphical User Interfaces (GUI)

MainActivity displays a flag and 6 buttons with texts from "First" to "Sixth".

The flag displayed changes according to the default language selected in the device (UK - default, Spain, Germany, France).
Different drawables support screen densities from medium (mdpi) to extra-extra-extra high (xxxhdpi).

All the strings of the application (TextView and Buttons) are also displayed in the default language selected in the device (English - default, Spanish, German, French).

The default layout arranges the Buttons vertically (like a 6 x 1 matrix).
Another layout will arrange the Buttons like a 2 x 3 matrix when the device is set in a landscape orientation (landscape).

In case of devices with an extra large screen (xlarge) a different layout will increase the text size of all the strings and display the Buttons like a 3 x 2 matrix.

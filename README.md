Android Things user-space drivers
=================================
Bunch of peripheral drivers for Android Things. If you need any other driver please let us know, we will do our best.

How to use the driver
-----------------------
Every driver is published as separeate lib to maven repository. 

Implemented drivers
-----------------------
Driver | Type | dependecy definition| usage  
:---:|:---:| --- | ---
[ULN2003](uln2003) | stepper motor| `compile 'com.polidea.androidthings.driver:uln2003:0.0.1-SNAPSHOT'` | [tutorial](https://gitlab2.polidea.com/pawel.byszewski/android_things_drivers/tree/master/uln2003) [sample](https://gitlab2.polidea.com/pawel.byszewski/android_things_drivers/blob/master/app/src/main/kotlin/com/start/bootstrap/example/StepperMotorActivity.kt)
[Numpad 12](numpad) | numpad with 12 buttons | `compile 'com.polidea.androidthings.driver:numpad12:0.0.1-SNAPSHOT'` | [tutorial](https://gitlab2.polidea.com/pawel.byszewski/android_things_drivers/tree/master/numpad) [sample](https://gitlab2.polidea.com/pawel.byszewski/android_things_drivers/blob/master/app/src/main/kotlin/com/start/bootstrap/MainActivity.kt) 

## License

    MIT License
    
    Copyright (c) 2017 Polidea Sp. z o.o
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.



## Maintained by

[![Polidea](https://raw.githubusercontent.com/Polidea/RxAndroidBle/master/site/polidea_logo.png "Tailored software services including concept, design, development and testing")](http://www.polidea.com)

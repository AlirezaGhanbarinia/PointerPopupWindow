PointerPopupWindow
==================

An extended PopupWindow which could add a pointer to the anchor view.You could set your own pointer image, this widget will compute the pointer location for you automatically.

![screen_shot][1]

Usage
==================
*For more usage see the `ppw-sample/` folder.*

1.simply use code:

        // create window
        PointerPopupWindow pop = new PointerPopupWindow(context, 200);//specify the window width explicitly
        // set content view
        pop.setContentView(content);
        // set pointer image
        pop.setPointerImageRes(R.drawable.point);
        // show popup window point to the anchor view
        pop.showAsPointer(anchor);
2.set align mode:

        // there are three kinds of built-in align mode are supported:DEFAULT, CENTER_FIX, AUTO_OFFSET
        p.setAlignMode(PointerPopupWindow.AlignMode.AUTO_OFFSET);
3.set margin screen:

        // margin screen are supported to avoid the window stick to the screen
        p.setMarginScreen(30);
        
        
Developed By
============

* OKry - <okry1123@163.com>

License
==================
Copyright 2014 OKry

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[1]:https://raw.githubusercontent.com/pinguo-marui/PointerPopupWindow/master/ppw-sample/screenshot/screen_shot.jpg

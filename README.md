# VI8

## Download - No More

For the sake of sanity, I have stopped uploading the APK for the "current" state of the application. So you will have to clone the repository and build it yourself.

## Initial Idea

The application is essentially a clone for 8pen, which for some reason they have stopped distributing. ( I can no longer install it even though when i paid for it!!!)

To understand what exactly this keyboard is please watch the video "https://www.youtube.com/watch?v=99vsUF4NuLk"

Now I will go ahead and shamlessly copy text from the original 8Pen website.

###### Handwriting reinvented
The vi8 draws inspiration from handwriting. By mimicking the way our hand moves when constrained to a square canvas, we are able to create a natural and fun writing experience, akin to doodling on a piece of paper.

###### Designed for speed
The layout is optimised for fast writing, by allowing for the most common letter sequences to be produced with swift, fluid gestures. Once familiar with the layout, you can reach speeds of 40 words per minute.

###### Typos, goodbye
The simplicity of the gestures used to enter words allow for true blind typing, and virtually eliminates typos, regardless of whether you have small or big fingers. Word suggestion becomes an optimisation, not a dependency.

## Extended Idea

The thing that bugs me, is that the most editing done on a mobile phones are those quirky message boxes and there is JUST NO WAY to edit stuff there.
And it is beyond frustrating to try and create a document on a mobile phone if it has more than twitter number of characters, and I feel like the 'text editors' for the mobile are like a joke with shit load of toolbars and stuff which you rarely open up to "edit" something because the problem remains, you just don't want to type on the mobile. it's tedious. it's time consuming. it's frustrating.

Then there came along 8Pen, the keyboard on which you can actually type blind, and I thought to myself now, Now, NOW, FINALLY!! Editing and creating a document/textfile would be practical enough on a mobile device and in the frenzy I turned to the plethora of text editors available on the various app stores. Yeah they get the job done, but you have to keep your both hands engaged and keep tapping on the various toolbars and buttons... I was missing [VIM](http://www.vim.org/).

I am a huge fan of Vim - the editor. It is so cool to be able to edit without leaving the keyboard, the idea that when you are editing you add less and modify more, it's so comfortable and it's bloody efficient. It works on desktop because you have a keyboard attached on which you can use all your, hopefully 10, fingers. On a touch screen, it is a very stupid idea to try to use vim.

I hear you say - "comeon! don't dismiss the idea without trying it first!". Believe me I did try, you can too, it's called [vimtouch](https://github.com/momodalo/vimtouch). Vimtouch, the port of vim on android, although a real big deal technologically, but utterly un-usable in a practical world setting. why? because at best you got 2 thumbs to do the job of a total 10 fingers. it's highly inefficient.

No matter what editor you use it has one basic issue, it works only when you open it. Think I am stupid? Let's try a practical, common, frequently occuring scenario. Your boss has sent you a mail and you are ANGRY! You want to reply to him/her and want to pour your heart out. you press the reply button and suddenly realize this is the perfect job for the editor!! so you search through your million installed app for that editor of yours and start editing. it takes you an hour to compose 5 lines and then you copy paste the stuff to the mail and you are done. The hassel!! 

And then it hit me... why the hell do you need the text editors? why can't your keyboard act as the editor? it's always there when you actually want to input/edit something, it's only and only software, no hardware to worry about, so you can hack the shit out of it. I mean WHY NOT??

And this inspiration (rant) became the idea for VIII - a Editor-in-Keyboard.

TO BE CONTINUED...

## Usability Guide

So, what capablities does VIII have?
Once you know how to type with this thing (Learn how to type with this original [8Pen-game App] (https://play.google.com/store/apps/details?id=com.eightpen.android.wordcup&hl=en), you must know the following 

##### Basic Needed Stuff

- Right Sector acts as a backspace Key.
- Bottom Sector acts as a Enter Key.
- Top Sector acts as a combi of SHIFT and CAPS_LOCK Key, i.e, Press once Shift is active, Press Twice CAPS is active and Press once more and everything is back to usual.
- Left Sector acts as the button that takes you to the Number Pad.

##### Cursor Movements 
If you move your finger from the centre-circle to any sector and stay, the cursor movement will be emulated. For example, if you swipe from circle->right, the cursor will move right. You get the picture.

##### Selection
There is selection built in to the keyboard. if you move your finger from the right sector to the circle, the cursor will start moving left and selecting everything in it's path. once you release, a selection keyboard will open up for various stupidities to do.

##### Paste Functionality
Moving your finger from right->circle->lift-your-finger performs a paste. whatever is in the clipboard.


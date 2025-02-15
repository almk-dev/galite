# galite
Modified version of the GalliumV2 keyboard layout

##### ortholinear
```
b l d w z j f o u ; \
n r t s g y h a e i '
x q m c v k p , . /
```
##### row-staggered
```
b l d w z j f o u ; [ ] \
 n r t s g y h a e i '
  x q m c v k p , . /
```
## changes
This layout is a combination of [GalliumV2](https://github.com/GalileoBlues/Gallium), [Graphite](https://github.com/rdavison/graphite-layout), and [Colemak](https://colemak.com/)[-[DH](https://colemakmods.github.io/mod-dh/)].

I wanted to accomplish the following:
- Retain the core layout of GalliumV2
- Have the same configuration for both row-staggered and ortholinear layouts
- Match the performance/stats of base GalliumV2 (disregarding punctuation)
- Simplify punctuation keys to be more "standard" and easy to switch from Colemak-DH/QWERTY
- Modify the left-hand side to prefer "extend" motions for middle/ring fingers and "curl" motions for pinky/index fingers:
  - This can't reasonably accomplished for the pinky finger without negatively affecting SBFs and pinky/scissor metrics
  - This is already the case for the middle/ring fingers
  - This is accomplished for the index finger by swapping `CV`/`WZ`, since the frequency(C) + frequency(V) is greater than the frequency(W) + frequency(Z)
- Have a less extreme top:bottom row usage ratio for the left-hand side than base Gallium
  - This is accomplished by swapping `CV`/`WZ`, since the frequency(C) + frequency(V) is greater than the frequency(W) + frequency(Z)
    - This brings the top:bottom ratio down from 2.85:1 to 1.91:1
   
## stats
![Screenshot 2025-02-14 at 4 01 12 PM](https://github.com/user-attachments/assets/86ea72b5-26f6-4f4c-9430-a5ff8f1137c7)

![Screenshot 2025-02-14 at 4 03 45 PM](https://github.com/user-attachments/assets/d16bbb2c-1283-497b-b134-ce8b2917e6be)

![Screenshot 2025-02-14 at 4 06 21 PM](https://github.com/user-attachments/assets/68b97426-dcc2-4d06-be35-5c23bcc959b0)

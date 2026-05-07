# qlyu0817_9103_tut1
My first repository for IDEA9103

This is my first local change to the repo!

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

**Bold Text** or _Bold Text_
*Italic Text* or _Italic Text_

- Item 1
- Item 2
  - Subitem 2.1
  _ Subitem 2.2

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2

1. First Item
2. Second Item
3. Third Item

1. First Item
1. Second Item
1. Second Second Item
1. Third Item

[Google Homepage](https://www.google.com/)

![An image of a kookaburra](https://cdn.pixabay.com/photo/2021/08/06/21/54/kookaburra-6527294_1280.jpg)

![An image of Mona Lisa](READImages/Mona_Lisa_by_Leonardo_da_Vinci_500_x_700.jpg)

Make sure to run `setup()` first.

```
function helloWorld() {
    console.log("Hello World!");
}
```

> This is a blockquote .


# Quiz 8 Answers

## Imaging Technique Inspiration

1. The example I found most inspiring is an interactive animated character that plays different instrument sounds when you click on different parts of the screen. Each click triggers a new sound layer, and they gradually stack up into a complete piece of music. What I'd love to bring into my project is this idea of progressive sound-layering through interaction, where the user isn't just listening, but actively building the music themselves. This technique fits my project well because it makes the experience feel like a performance, and the payoff of hearing everything come together is genuinely satisfying.

## Coding Technique Exploration

2. The coding technique I'd like to use is p5.js with the p5.sound library, specifically loadSound() and mousePressed() to trigger and layer multiple audio tracks interactively. Since my role focuses on using sound level or frequency content to drive the project's mechanic, this is a natural starting point. Each click adds a new audio layer, and from there, p5.sound's amplitude and FFT tools can read the live level or frequency data to drive visual changes, directly linking user interaction to the core behaviour of the project.

### Reference images and coding techniques

[Google Homepage](https://www.google.com/)

![load and play sound coding technique 1](https://editor.p5js.org/p5/sketches/Sound:_Load_and_Play_Sound/)

![An image of load and play sound 1](READImages/loadandplaysound.jpg)

![load and play sound coding technique 2](https://websoundart.org/articles/20231217_tutorial-6-p5sound/)

![An image of load and play sound 2](READImages/loadandplaysound2.jpg)

![play and pause coding technique](https://editor.p5js.org/kjhollen/sketches/ByZILENim/)

![An image of play and pause coding technique](READImages/playandpause.jpg)

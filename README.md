# FeBe CSS Reset

## Why another reset?
This is a fair question. There are a ton of resets out there. I think the gold standard has generally been Eric Meyer’s CSS Reset or Normalize.css. But these resets are bare bones and just make elements behave the same way. 

FeBe CSS Reset is intended to also reset and normalize typographic heuristics and provides a library of helper classes. What you end up with is a reset that’s also ready for rapid-deploy primetime with minimal styling required.

### Human and Machine Readability
Most resets don’t take typography or machine readability into account. It’ll reset things like <cite> and <q> but not normalize their typographic display in a meaningful way. This means a lot of designers will use other elements like <b> or <i> or custom classes instead of using machine readable tags that already exist.

### Deprecated Elements / Older Browser Support
The FeBe CSS Reset keeps deprecated elements separate to make progressive enhancement / graceful degradation easier to control.

### Easy to Customize
Because this reset mostly focuses on typographic standards, you can customize it quickly and easily.

### React Ready
FeBe CSS Reset was specifically designed for newbie use in React apps created with the npm create-react-app script. There are a few ways you can use this in your React Project.

1. _**Recommended:**_ Copy it directly into your **src** folder and add `import './febe-css-reset.min.css';` to your **App.js** file.
2. Use it to replace the contents of your **App.css** file in the **src** folder. 
3. _Not recommended:_ Add it to your **public** folder and reference it directly from the `head` of your **index.html** file.

## What It Doesn’t Do (and why)
You’ll notice that Febe CSS Reset doesn’t deal too much in terms of width, positioning, and background or border styles. There are a few exceptions to ensure a gorgeous site can be rapidly deployed. There are some templates for box-border and border-radius and tables, but going much further would start to get into straight up templating. That’s something better handled by resources like Bootstrap or Flexbox.

## The Demo
The demo is used with FeBe CSS Grid to show off what’s possible typographically with just this one file and only a handful of custom classes.

The demo also includes an inline JavaScript goodie. Something that shows up pretty consistently on Stack Overflow is any variation of the question, “How do I display the current year in a copyright notice?” And usually someone replies, “Oh, you shouldn’t *just* display the current year because that’s bad copyright practice, you should be displaying a year range starting.” 

So here’s where I blow your mind: the demo includes a single line of best-practice code for displaying the copyright notice that you can copy and paste into literally any project. No external libraries needed.

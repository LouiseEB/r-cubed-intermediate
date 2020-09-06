# For Instructors

![](https://img.shields.io/badge/document%20status-revising-orange?style=flat-square)

## Course details

- **Instructor and helper number**: The recommended number of instructors would
be about ~1 instructors for every 1-2 sessions, with a ratio of 1 helper
(including instructor) for every 5 participants.

- **First day**: During the introduction, don't forget to introduce all the
instructors and helpers.

- **End of course**: Ask if any participant would like to be involved in next
year's teaching, or in making the material, or in being a helper.

## Instructor tips

### Before your session

- Have an RStudio theme that uses a white background with black text.
This setting is easier to read on projectors.
- In "Global Options -> Appearance", 
put a higher Zoom value and increase the font size (maybe around 14). 
Exact zoom and font size depends on the projector.
- Put the Console and Script panes side by side rather than stacked. 
This can be changed in the "Global Options -> Pane Layout" 
- If the instructor team is sharing a code-along repository (e.g. so there is
continuity between session), make sure to pull the latest changes from the
previous session.

### Throughout the sessions

- For most of the sessions,
there are sections that tell the participants to read on their own.
Know beforehand where these sections are and
get them to read over the section.
Ask for any questions about what they read, 
and if you want to elaborate you can, 
but it's not necessary given they just read it.
- There are also areas called "Details for instructors" that has notes or
comments about something to focus on or reinforce for a concept. Make sure
to know where these are and to use them to help you as you go through the material.
- For the exercises, make sure to get the learners helping each other out in
their pairs.
- Exercise solutions do not need to be covered by the instructor,
given the solution is provided already.
    - During the exercise, copy and paste the solutions from the site into your
    code-along R Project, so you can move to the next section quickly.
- Try to keep the screen on your RStudio as much as possible 
and don't switch applications often, 
only when you need to go to the course material or to show an exercise.
- Be aware of how much space you have on the projector screen 
and don't let R code go too long. 
You have two options to take so that all code stays on the screen
(use which ever you find most visually appealing):
    1. Use soft-wrapping of R code. 
    You can set this in RStudio by going to "Tools -> Global
    Options -> Code -> Editing tab"
    and then tick the "Soft-wrap R source files" option.
    2. Or, adding more lines to the code then you normally would use.
    For instance, instead of:

        ```r
        ggplot(NHANES, aes(x = BMI, y = Age, colour = Diabetes)) +
            geom_point()
        ```
    
        You could add new lines like:
    
        ```r
        ggplot(NHANES, 
               aes(x = BMI, 
                   y = Age, 
                   colour = Diabetes)) +
            geom_point()
        ```

- After exercises have been completed, get someone to tell you what to write.
Make sure it matches approximately what the actual solution is.

- If a section doesn't mention for the student to read it, that means the
instructor should mention and talk about it. But don't read it word for word,
instead talk about it while doing the code along. It's strongly suggested that
you try to use your own words rather than exactly what was written. This makes
it easier for you and makes it more engaging for the learners.

### Making use of the stickies

- Check in with the learners to see where they are at by asking something like:
"Do you see the same thing as is on the screen?"
If yes, put the 'all good' sticky on your laptop. 
If no, use the 'need help' sticky."
- For the reading activities, before starting, say:
"Please read this section as instructed. 
When you are done, put the 'all good' sticky up."
- For exercises, before starting, say:
"Please complete the exercise. When you are done,
please put the 'all good' sticky up.
If you need help, put the 'need help' sticky up."

## Lesson material details

### About the slides

The slides are generated from the [xaringan] R package,
which uses [remark.js].
In the slides, there are notes that you can read 
either by going to the source `.Rmd` file 
or by opening the slides and hitting the `p` key.
To use the slides more efficiently, 
check out the [remark.js keyword shortcuts].

[remark.js]: https://remarkjs.com/#1
[xaringan]: https://github.com/yihui/xaringan
[remark.js keyword shortcuts]: https://github.com/gnab/remark/wiki/Keyboard-shortcuts


# social-media-indirect-signal-detector
A simple logic-based system that detects when someone might be sending indirect hints or messages about you on social media through pictures, captions, stories, likes, or emojis.
 3. Basic Logic Code 

A. Picture Detection Logic

If a picture contains something related to my life:
    Mark = "Maybe about me"
Else if picture mood matches recent talk:
    Mark = "Indirect signal"
Else:
    Mark = "Not about me"

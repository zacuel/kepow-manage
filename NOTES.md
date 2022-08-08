the way heading tags work (h1,h2, etc)

h tags create some kind of "section" including everything after until another h tag; mostly(?) for screen readers/accessability.
    -Sort of like chapters in a book. 

Kevin uses H tags symbolically and syles them with custom classes 
(based on the original variables we set from analyzing the goal image) rather than parent styles. 
By setting the margin, padding, font-size and style of everything to "inherent"
Everything will look the same unless styled otherwise. 

ON SCREEN READERS/ ACCESSABILITY

for images use alt tag
for other elements use aria-label
h tags also serve the purpose of aria labels because they are read as main events, allowing small stuff after to be skipped over. 
it's good to accurately aria-label of li parents, to describe the list for a screenreader user. 
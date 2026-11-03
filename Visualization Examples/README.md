# Visualization Examples

This page showcases data visualization projects completed as part of CMSI-670. Each example includes a screenshot, a link to the interactive visualization, an explanation of how to use it, and a discussion of the design choices behind it.

---

## Visualization 1

![Visualization 1](https://github.com/lilscolari/CMSI-670/blob/main/Visualization%20Examples/Visual1.png)

**Website:** [View Interactive Visualization](https://www.hoopstreak.com/stats/passing)

### Overview
This is an adjacency matrix visualization that showcases how players on a certain team pass to one another. The horizontals represent the passer and the vertical encodes the player receiving the ball. The players are sorted by who makes the most passes so the marginal frequencies on the right will be sorted from largest to smallest while the ones on the bottom may not be in order, highlighting players that may pass the ball more, and those that may receive the ball more.

### How to Use
The main page displays all 30 teams in a small multiple view with a default of 8 players displayed per team. However, this slider can be moved to dynamically update the view for all teams. Auto-generated text is displayed below each grid highlighting the top connection and how much % of a team's passes the top passer makes. Hovering over squares or player images in the graph changes the text displayed. A players face reveals how many passes a player makes and receives and to whom and from whom they pass and receive the most from. Hovering a square in the matrix displays how many passes that horizontal player makes to the vertical player. It also displays how many assists that combo has and the shooting percentage that player has after the pass. You can use one of the dropdown menus to change seasons and the other to select an individual team to analyze even further. In basic mode, the color gradient represents the number of passes made relative to the league with the lower colors being fewer. In advanced mode (toggled by selecting the checkbox), the color now represents the points per shot after the pass relative to the league with blue being below average and red being above average. The size now represents the number of passes relative to the league. In advanced mode, the hover now changes the text to also display the average points per shot of each square.

### Design Choices
TODO: Explain the reasoning behind the visualization's design. Consider:
- Why this particular chart type was chosen.
- Why specific colors were used.
- How the layout helps communicate the data.
- How the design makes the visualization easier to understand.

I chose to design this chart type because I have not seen it done before for basketball and I thought it was a super unique way to visualize how players interact with each other on the court. It is super important to understand which players pass the most amongst each other to understand how a team's offense operates. It is also important to see the tendencies of the receiving player after the pass. Do they shoot? If they do shoot, do they shoot well? I used the color gradient from blue to red to represent the real world model of cold and hot. At first, I thought of using green and red because those are universally known to represent good and bad. However, this decreases usability and generalizability for users who may be colorblind and mix those colors up. The small multiple helps highlight how different teams run their offense differently. One player might make a majority of the passes or receive a majority of the passes on one team while other teams may have a much more even spread. The average points per shot coloring also allows you to immediately find the player combinations that are the most effective at on certain teams. The marginal distributions allow uses to immediately understand the total passes players make and how that differs from their teammates. The slider allows you to keep the same dimensions of the data, but either focus on the whole team or only the most active players. The basic vs. advanced mode was something I valued a lot because I feel like a big aspect of design is making the users feel like they are in control and allowing for users of different backgrounds to understand the data. A novice at basketball data may be overwhelmed by the advanced mode and may extract better meaning through the basic mode while a high-level analyst may prefer the advanced mode for the extra metrics it displays. The design may take a few minutes to get used to, but once you understand it, the concept is consistent and easy to visualize.

---

## Visualization 2

![Visualization 2](ADD_IMAGE_LINK_HERE)

**Website:** [View Interactive Visualization](ADD_WEBSITE_LINK_HERE)

### Overview
TODO: Describe what this visualization represents, what data it uses, and its main purpose.

### How to Use
TODO: Explain how users can interact with the visualization. For example, describe any filters, buttons, hover effects, or interactive elements.

### Design Choices
TODO: Explain the reasoning behind the visualization's design. Consider:
- Why this particular chart type was chosen.
- Why specific colors were used.
- How the layout helps communicate the data.
- How the design makes the visualization easier to understand.

---

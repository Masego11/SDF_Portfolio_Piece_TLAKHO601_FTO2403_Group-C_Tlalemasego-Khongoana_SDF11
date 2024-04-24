**Project objectives**

- Clone the provided starter code.
- Creat a responisve navigation bar my landing.
- Develop a hero section of my landing page using tailwond css.
- Detail the services and features of cache bank ensuring that each aspect is     visually attractive and clearly explained.
- Present cache features in an organised and appealing way using grid and flex and tailwind to maintain look and feel.
- Condtruct a section that showcases Cache Bank's impact through statistics including Getting started call to action.
- Make data and statistics engaging and informative.
- Add a contact section and a comprehensive footer focusing on accessebility and functionality.

## Project breakdown

**Body Container**: 
- Body background color set to bg-slate 200 ,a lighter grey theme color to ensure all content appears clearly 

## Component 1/Header Section**: 

**Header Class**
- Header section centered horizontally.
- background color set to white.

**Main container with header content**
- Main container with header content set to Position relative to alow elements within container to adjust to screen sizes.
- Display set to flex.
- flex wrap to allow flex items to wrap when screen size is reduced
- Elements centered horizontaly, 
- Elements spaced between to create equal spacing between elements.

**Logo image content**
- Image class given a height-10 to scale it down and ensure consitency on smaller screens

**Nav Items parent container**
- Used hidden utility to hide items on smaller screen 
- Set text color to black 
- Added a gap-12 between nav items
- Nav items centered horizontally
- Justified space-between to create equal spacing between elemenets 

**Nav items anchor tags**
- Styling applied across all four anchor tags
- font size set to small
- font weight set to normal
- Added green color effect when hover on 

**Input button**
- Same styiling to nav items in anchor tag container

**Sign up button**
- Added padding-4 to left and right 
- Added padding- 2and to top and bottom
- Rounded corners of my buttom,background 
- Background color set to green and pink when hovered on

**Hamburger SVG**
- Hamburger svg hidden on larger screens
- Uniform padding-4 applied to svg

**Nav items when inside hamburger svg**
- Display set to flex
- Hidden utility to hide items on medium and large screens
- flex col used to stack vertically
- items start used to aling to the left, 
- width of itmes set to 100% ensuring they take full width of parent container 
- gap-3 between flex list items, 
- Horizontal pading-4 for left and right side
- Vertical padding-8 for top and bottom
- Changed text colour to w.
- Reduced button and font size.

## Componenet 2

**Section class**
- Display set to grid layout
- Container set to 100% width, 
- Number of grid columns set to 1 
- Margin-auto applied to center elements vertically, 
- Margin top-12 applied  to push grid down from the top
- Margin bottom-8 adds bottom margin to create space grid between elements below

**Div class for heading, paragraph and buttons**
- Display set to flex
- Flex children stacked vertically
- Flex children centered horizontally
- Children to ocucupy one column
- Text set align to the left on large screen sizes

**Heading class**
- Margin bottom-8 set to create space below element, 
- Font size set-4xl on medium screen and to 6xl on large screens
- leading tight utility used  to reduce space between ligns of text

**Paragraph class**
- Margin bottom-6 set to create space below element
- Font size set to base, 
- Line height set to create moderate spacing between lines of text
- Width of parent container set to 75% on large screens 

**Buttons class**
- Styling applies to both buttons
- Vertical padding-4 added
- Font size set to small
- Font weight set to bold, 
- Button text color set to white
- Background color set to green and pink when hovered

**Image container**
- Display set to flex
- Flex children pushed to the right side of the page
- Children hidden on small screens
- Children to occupy one column
- Children to be visible on medium and larger screens

**Image class**
- Image to occupy 80% of its parent container width 

**Section class for endorsements**
- Children of container take up full width of the page

**Endorsements parent container**
- Display set to flex 
- Children to stack vertically
- Children centered horizontally
- Gap-4 Between flex children
- Direction changes from vertical to horizontally on larger screens

**Paragraph class**
- Font color set gray
- Font weight to semi-bold 
- Margin-10 added to bottom
- Text size set to 2-xl

**Container for svgs**
- Svgs to align horizontally
- To wrap into a signle row on small screen sizes
- To take 100%width of parent container
- A gap-6 between them prevents wrapping on large screens
- Set to align with even spacing between on larger screens 

- Grid to have 2 columns on medium screens for responsive layout
- Gap-14 set between grid cells on xl screen size
- Gap-5 set between grid cells set to-14 on medium screen size

## Component 3

**Parent container**
- Added margins to left and right of container
- Added padding top and bottom
- Display set to flex 
- Flex children to stack vertically
- Flex children centered horizontally

**Card section**
- Display set to grid
- 1 grid column layout for smaller screens
- 2 column grid layout for medium screens
- 3 column grid layout for larger screens
- A gap-10 between grid items
- Margin top-10 above grid items

**Card container**
- Styling to apply to all cards
- Display set to flex
- Flex children to stack vertically 
- Flex children centered horizontally
- Padding-5 added on the sides for space
- Padding added to top and bottom for spacing to prevent content from touching edges
- Extral large rounding around corners
- Pre-defined shadowing applied 
- Gray color effect when hovered on
- Hover effect to have a transition of 300ms

**SVG container**
- Styling to apply to all svgs
- Display set to flex
- flex citems to stack vertically, 
- Flex items centered horizontally
- Width and height set to-12
- Corners rounded-2xl
- color of svg 1-3 set to green
- color of svg 4-6 set to pink

**Parent container for text content**
- Styling to apply across all cards
- Display set to flex
- Flex children to stack vertically 
- Gap-2 between flex children
- Text content aligned to center
- Horizontal padding of-6 to content from touching edges

**Header class**
- Styling to apply across all cards
- Font size set to 2xl
- Weight set to extra bold
- Font color dark gray

**Paragraph class**
- Font weight set to medium 
- Font color set to dark gray dark

## Component 4

**Parent container**
- Children to take up full width of parent container

**Container for stats,text and options**
- Display set to flex
- Flex childrne to stack vertically
- Flex children centered horizontaly in a column layout, 
- Vertical gap-16 between flex children
- centered the container horizontally by adding margins to sides
- Added margin top-32 to create room between flex children

**Parent container for statistical blocks**
- Display set to grid
- Children to tak up full width of parent container 
- 1 column layout on small screens
- 2 columns on medium screens
- 4 column layout on larger screens
- gap of-8 between grid rows for consistent vertical spacing

**Main container for stats**
- Display set to flex
- Flex children to set stack vertically
- Flex children centered horizontally

**Container for number**
- To Apply across all stats
- Font size 5xl
- Font weight extra bold
- Line hieght adjusted to creduce gap between lines of text 
- Text centered
- Text color dark gray

**Container for stat text**
- Styling to apply across all stats
- Font size set to default
- Font weight set to moderately bold
- Line height set to 7 for balanced amount of spacing betweeen lines
- Text centered horizonatlly
- Color set to gray

**Parent container**
- Set to take full width of parents container 
- 1 column grid for smalller screens
- Set to change to 2 columns on larger screens
- Gap of-32 between grid items 

**Container for heading and options**
- Display set to grid
- Children set to take up full width of container
- 1 grid column on small screens
- 2 grid columns on large screens
- gap-32 between children

**Image class**
- Background image to cover entire element
- Hidden utility applied to hide picture on smaller screens
- Image visible on larger screens

**Parent container for heading and options**
- Display set to flex
- flex children to stack vertically
- Vertical gap 16 added between flex items

**Container for heading**
- Display set to flex
- flex children to stack vertically
- Vertical gap-2 between items
- Text centered horizontally 
- Text to align to the left on medium and screens

**Heading class**
- Text size set to 3xl on small screens
- 4xl on medium screens and 5xl on larger screens 
- Font weight set to extra bold
- Color dark gray

**Text class**
- Font size set to default 
- Font weight to moderately bold
- Line height set to 7 for balanced amount of spacing betweeen lines 
- Color set to gray-700 

**Options parent div**
- Display set to grid
- Grid to span full width of parent container, 
- Set to 1 column on smaller screens
- 2 columns on larger screens
- vertical gap-16 between rows and horizontal gap-10

**Option child div 1**
- Styling to apply accross all children
- Display set to flex
- Children to stack vertically
- CHildren aligned to the left
- Created a small gap between flex items

**Option number div**
- Styling to apply accross all option numbers with option 1&4 with green background nd 2&4 with pink background
- Display set to flex
- Children to stack vertically
- Children centered horizontally
- Width set to 12, hieght set to 12
- Border radius rounded
- Margin bottom-2 added

**Option text div**
- Styling to apply across all options
- Font size set to default
- Font weight medum
- Line height set to 7 for balanced amount of spacing betweeen lines
- text colour set to white 

**Option heading class**
- Styling to apply across all options
- Font size set to default
- Font weigh to bold
- Line hieght adjusted to creduce gap between lines of text

**Option text class**
- Styling to apply across all options
- Font size set to default 
- Font weight medium line height set to 7 for balanced amount of spacing betweeen lines
- Text colour set gray

## Component 5

**Contact section div**
- Elements to take up full width of screen

**Grid div container**
- Display set to flex
- Flex children to stack vertically
- Flex Children centered horizontally 
- Gap-16 between flex children
- Mx-auto to center container horizontally in parent div
- M-32 to add margin to and bottom 

**Parent div for cards**
- Display set to grid
- Grid to span the full width of parent container
- 1 grid column on small screens
- 2 grid column on medium screes 
- 3 grid column on larger screens 
- Gap 5 between grid items

**Card child div**
- Styling to apply across all cards
- Display set to flex
- flex children to stack vertically
- flex children centred horizontally 
- Gap-3 between flex items 
- Padding-8 to left and right side
- Padding-10 to top and bottom
- Background set to white, 
- Shadow effect applied 

**Text class for phone email and location**
- Styling to apply across all cards
- Text size set to 2xl 
- Font weight to extrabold
- Color dark grey

**Text class for text**
- Style to apply all cards
- Font size set to default
- Text size set to small 
- Line height set to 7 for balanced amount of spacing betweeen lines
- Text colour set gray

**Text class for contact info**
- Styling to apply across all cards
- Font size set to large
- Font weight set to bold 
- Color set to green

**Footer Section Parent div**
- Elements to span full width of parent container
- Background color set to green
- Container centred horizontally to ensure it is in the middle of viewport

**Parent container for icons and text**
- Display set to flex
- Flex children to stack vertically

**Container div for icons and text**
- Display set to flex
- Flex children to stack vertically
- Flex children centered horizontally
- Width-full to ensure container spans full width 
- Margin top and bottom 20 to ensure container has space above and below 

**Parent div for icons**
- Display set to flex
- Flex children to stack vertically 
- Flex children to align horizontally
- Gap-6 betwen flex children 
- Margin-8 to the bottom

**Icons main div**
- Display set to flex
- Flex children centred horizontall
- Gap-8 added between children

**Icons class**
- Styling to apply across all icons
- Icon colors set to dark blue
- Hover effect of gray

**Text div**
- Display set to flex
- Flex children aligned to center

**Text class**
- Font size set to default
- Font weight set to normal
- Line height set to 7 for balanced amount of spacing betweeen lines
- Text centered

**Challenges**
- General understanding of project assets 

**Google slides**
https://docs.google.com/presentation/d/1oK-rxkyaSumo7LUnu1qsA9UN9u-b2Tdh/edit#slide=id.p4

**Loom presentation**
https://www.loom.com/share/6ad7109807294814a856e59b416d3a99?sid=47c02a06-6385-4a17-94d3-f800d0921ed7

# Presentation Talking Points and Presentation Slide Template
Check out the Project Overview in this GitHub Repo for the guide to talking points for your presentation as well the starter template for your Google Slides here: https://github.com/CodeSpace-Academy/SDF_Portfolio_Piece_StudentNo_Classcode_Group_Name-Surname_SDF11/blob/main/11_portfolio_piece_1.md

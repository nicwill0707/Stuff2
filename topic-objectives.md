1. The map I would like to create for my final map will be an extension of a pre-
existing map that I created in MAP 671, which was a map of trees on University of
Kentucky Campus. The geographical extent of this data is much different from the
other data sets we have worked with so far in this course, as all of the almost
6,000 trees in the dataset provided to me by UK Physical Plant Division are within
a 600-acre area of UK Campus north of Cooper Drive. Currently, this map exists on
a website that I administer, found at this URL: https://ukntrees.ca.uky.edu/ . I
have since realized that "UK Interactive Tree Map" isn't terribly sexy, and so I
will consider dropping the word "interactive" for the 2.0 version I am envisioning
for the final in MAP 673.
2. I am making this map because I work as an extension associate of urban forestry
in the UK College of Agriculture, Food and the Environment, and much of my time
is spent thinking about urban trees and greenspace. Tree inventories are becoming
an important part of urban forestry management and research, but they also
represent an opportunity for outreach and education about the important resource
that is the urban tree canopy in our cities. There are several really interesting
takes on tree maps online already, one example being the Melbourne Urban Forest
Visual (http://melbourneurbanforestvisual.com.au/#mapexplore) and the New York
City Parks Street Tree Map (https://tree-map.nycgovparks.org/). These maps use
Carto and Leaflet, respectively, and in many ways have served as the model for
the existing map on our UKnTrees website.
Something I hadn't done before I created the existing Carto map was imagine a
persona which would be using the map. I work for scientists who study forest
systems, and their input was what has most shaped the functionality of the
existing map. I would benefit greatly from imagining a regular Joe or Jane who
has a mild interest in trees who happens to stumble across our website and map.
I am imagining that Joe/Jane could be overwhelmed with the 6,000 markers
of differing colors on the screen, as well as the orange building polygons which
represent a multi-year class research project. In general, I think a user with
mild interest (nearer to the southwest corner of Roth and Harrower's (2008) user
motivation vs. interface complexity model), might be scared off by appearance
of the map as it exists.
My goal then, is to reconfigure the map with filters and a few UI options so that
the initial map that Joe/Jane sees (1) less intimidating, (2)easier to navigate,
(3) more fun! If possible, though, I actually want to add more functionality for
the hard-core tree enthusiasts (its a thing, really), while accomplishing goals
1, 2 and 3.
3. I have a good working relationship with UK PPD and specifically the campus
arborists who manage this data set. The tree inventory is actually a living
dataset which these folks use and update dynamically as trees are removed and
planted. The data is accessed and manipulated by UK PPD using some proprietary,
ArcGIS-based software which was developed by ArborPro, the California company who
was contracted to complete the inventory. I am trying to convince UK PPD to migrate
the data out of this software (that's a whole other conversation), but whatever
the outcome I have access to the data basically whenever I need it; as it can be
exported as a shapefile and shared. Since the dataset is dynamic, I'd like to
pull down the latest tree data on a yearly basis to keep the trees on the map up
to date, but I'll worry about this when I get some job security that lasts longer
than 6 - 8 months.

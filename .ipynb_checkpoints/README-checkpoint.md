# Traffic Violation Detection
 Joseph Rosenblum


### Table of Contents

### Executive Summary

### Folder Structure

### Problem Statement
Protests occuring through the summer of 2020 have indicated that there is a significant amount of public distruct regarding current policing methods.  The public has been divided by such proposals as to defund the police.  While there is a worthwhile discussion to have around these proposals, such proposals often conflate police with law enforcement, and overlook an area of potential imporovement in doing so.

One of the most dangerous types of interactions police are those which take place during car stops.  While most of these stops are initiated for simple infractions, circumstances may cause these situations to escalate into involving crimes, violence, and arrests.

Car stops are officer-initiated occurances.  They generally involve an officer observing a violation being committed, and then making an attempt to stop the vehicle to issue the motorist a summons.  Often before a summons is issued, an officer must insure that the motorist is properly licensed to drive and is not already wanted on a warrant.

This is essentially a proactive policing action, as opposed to those vehicle stops which occur because an occupant of the vehicle is suspected of having committed a crime.

All policing is inherently biased, as people performing the policing bring with them their own human biases.  There is some instinctual understanding of this by the general public, which has lead to the distruct of police.  The nuance of the actual biases of police are dwarfed by politicized viewpoints of what they are. Both the external viewpoints of those who see police bias as an integral part of the marginalization of some parts of American society, and the internal viewpoints some in police have...

At the same time there are calls to defund the police, automation is defunding employees of many industries as human labor is replaced with automation.  There is a natural area of overlap here: police reform can take a queue from reform elsewhere in our society and replace human capital with ai.

There are additional reasons to consider this a good thing.  Here are a few:
Most traffic violations are not enforced.  There simply are not police present when they occur.  Uneven enforcement is unfair
More traffic enforcement should take place.

While we don't want to be called out as individuals for doing anything improper behind the wheel, the overall impact of increased enforcement be a net gain for society.

However, car stops for traffic infractions are not, in general, an effective method of traffic enforcement.  The potential cost is too high for too small a gain society.  That is, nobody, Police Officer or civilian, should be put at risk over a minor traffic infraction.

I propose leveraging advanced object recognition techniques into traffic inforcement cameras to vastly broaden their capabilities. 

Currently, red-light camera systems and speeding systems exist and are broadly implemented.  These systems are [expensive to purchase, install, and maintain.](https://www.cdc.gov/motorvehiclesafety/calculator/factsheet/redlight.html#Costs)  These systems are each limited to only red-lights or speeding.  Each state and local government has thier own standards to follow for implementation of these devices.  In [New York State](https://www.nysenate.gov/legislation/laws/VAT/1111-A), for example, each city of one million residents or more may hold a vehicle owner liable for fines associated with violations detected by these camera systems, but are only allowed to install them at a maximum of 150 locations.

machine-learning-based approach could be both less expensive and more effective.
To demonstrate low cost, this project will use data generated from inexpensive web-cams, typically costing no more than $100.  To demonstrate effectiveness, this project will focus on enforcement of vehicles stopped in a crosswalk, which is both dangerous for pedestrians and infrequently enforced.


### Data Acquisition
Most of the data used in this project was originally created as part of the project [Understanding Traffic Density from Large-Scale Web Camera Data](https://arxiv.org/abs/1703.05868).  Data in this set included custom .XML annotations for each vehicle.
Additionally, YOLOv5 is trained on the COCO dataset.

### Data Description
Data consists of low-resolution webcam footage taken in various locations around New York City.  All images are formatted to 352 x 240.

### Software Requirements

### Data Cleaning Steps

### Exploratory Data Analysis

Using default coco-trained weights gave results

### Data Processing

### Engineer Features

### Modeling

### Evaluation

### Conclusion

### Next Steps

detect people & vehicles, signal lights?
determine proximity to crosswalk
signal if
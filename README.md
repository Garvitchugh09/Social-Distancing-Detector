# Social-Distancing-Detector


# Social-Distancing:
Social Distancing is a methodology in which humans stay away from each other physically. 

# Requirement:
- yolov3.cfg (configuration files
- yolov3.weights (trained model to detect objects)
- coco.names (Dataset of 80 objects)  

The project detects the human beings from any recorded video or image or we can also use live camera. It tells us about the safe ditance that should be maintained in order to be safe from diseases(like COVID-19). It plots different color rectangles and lines to show the level of risk(DARK RED: HIGH RISK,ORANGE: LOW RISK,GREEN:SAFE).It also gives total numeber and the number of people in RED ZONE, ORANGE ZONE and GREEN ZONE.
It calculates the distance between the people using Euclidean distance.

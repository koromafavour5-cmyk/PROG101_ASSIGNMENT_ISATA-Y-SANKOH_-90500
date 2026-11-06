# PROG101_ASSIGNMENT_ISATA-Y-SANKOH_-90500
A community waste management project that promotes cleaner neighborhoods through better waste collection, sorting, and awareness.

## Overview
Community Waste Management is a project that addresses the growing problem of waste in residential neighborhoods. In many communities, garbage piles up in streets, drains, and open spaces because collection is irregular, disposal points are limited, and many people don't know the effects of improper dumping. This project offers a more organized and sustainable way to handle that waste.


## Problems 
In many communities, waste is dumped in streets, drains, and open spaces because there are too few collection points and little awareness of proper disposal. This leads to:
Health risks: diseases spread by flies, rodents, and contaminated water
Flooding: blocked drains and gutters
Pollution: foul smells, plastic buildup, and burning of waste that harms air quality
Poor living conditions: dirty surroundings that lower quality of life and community prideThis project offers a practical, community-based approach to managing waste by tackling it at every stage, from the household to final disposal.

## Solutions 
1. Organized collection
Set up regular collection schedules and designated collection points
Place waste bins in busy areas such as markets, schools, and street corners
Track collection so no area is left uncovered
2. Waste sorting and recycling
Encourage households to separate plastics, organic waste, and general refuse
Reuse organic waste as compost for gardening and farming
Collect recyclable materials like plastic bottles and cans for reuse or sale
3. Community awareness
Run clean-up campaigns and neighborhood sensitization programs
Teach residents, especially children and youth, about the health and environmental effects of waste
Recognize and reward clean communities to build pride and participation
4. Community participation
Involve residents, youth groups, and local leaders in keeping the area 

## SDG 6 aims to make sure everyone has access to clean water and proper sanitation. Community waste affects this goal because garbage dumped near streams, rivers, and open spaces pollutes drinking water, while waste that blocks drains causes flooding and stagnant water that spread diseases like cholera, typhoid, and malaria. Rotting waste also leaks liquid into the soil that can contaminate wells, and piles of rubbish attract flies and rodents that make living conditions unhygienic. This project supports
by collecting and disposing of waste properly, encouraging sorting and composting, and teaching residents not to dump waste in drains and water sources, so that water stays cleaner, drains stay clear, and the community stays healthier.

##PSEUDOCODE 
BEGIN

DISPLAY "Community Waste Management and Collection System"

INPUT resident_name
INPUT location
INPUT contact_number
INPUT waste_type
INPUT waste_quantity
INPUT collection_request

IF resident_name is empty OR location is empty THEN
    DISPLAY "Required information is missing"
ELSE
    IF location is supported THEN
        CREATE new collection_request
        SET request_status = "Pending"

        IF waste_type = "Organic" THEN
            SET waste_category = "Biodegradable"
        ELSE IF waste_type = "Plastic" THEN
            SET waste_category = "Recyclable"
        ELSE IF waste_type = "Metal" THEN
            SET waste_category = "Recyclable"
        ELSE
            SET waste_category = "Other"
        END IF

        CHECK collection_team_availability

        IF collection_team is available THEN
            ASSIGN collection_team to request
            SET request_status = "Scheduled"
            DISPLAY "Collection request scheduled"
        ELSE
            SET request_status = "Waiting"
            ADD request to waiting_list
            DISPLAY "Request added to waiting list"
        END IF

    ELSE
        DISPLAY "Location is not currently supported"
    END IF
END IF

REPEAT
    CHECK waiting_list

    FOR each waiting_request
        IF collection_team becomes available THEN
            ASSIGN collection_team
            SET request_status = "Scheduled"
            REMOVE request from waiting_list
        END IF
    END FOR

UNTIL waiting_list is empty

GENERATE collection_report
DISPLAY collection_report

END


## Flowchart 


Author Isata Y Sankoh 
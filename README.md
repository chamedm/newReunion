# newReunion


## Micro Service Description
Gathers information about the participants and the conditions of the reunion

## Functional Requirements
- Creates a new reunion liked to all participants
- Should get information about the number of people and their contacts
- Should get information about whether or not people is actively wearing mask
- Should get information about how much time the reunion lasted
- Should get information about whether or not was an open space (air flowing)
- Should get information about the volume of participants - regular talking, singing, screaming (aerosoles)
- Can apply CRUD operations on the reunion

## Non Functional Requirements
- The reunion state is calculated (with calculateRisk microservice) based on information added here
- Updates risk% a little after the reunion is created

## Deployment URL



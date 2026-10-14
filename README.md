<html>
  <head>
    <h1>
      Group 3.7 Engineering project
    </h1>
  </head>

  <body>
    <p1>
      ```plantuml
          @startwbs
          * Goose Game
          ** Website 
          ** Requirements
          *** Research
          **** Customer Interview
          **** Product Brief
          **** Researching Similar Products
          *** Write up Requirements
          **** Functional Requirements
          **** Non-functional Requirements 
          ** Architecture
          ** Risk Assessment and Mitigation
          *** Write up Risk Assessment
          *** Design a Risk Mitigation Plan
          **** Write up Risk Mitigation Plan
          ** Implementation
          *** Implement Frontend
          *** Implement Backend
          *** Backend-Frontend integration
          ** Testing
          *** Design Testing Plan
          *** Test Implementation
          *** Write up Test Plan
          ** Design
          *** Design Frontend
          *** Method Selection  
          *** Method Planning
          @endwbs
      ```
    <\p1>
    <p2>
      ```plantuml
         @startgantt
         printscale daily zoom 2
         Project starts the 14st of October 2026
         [Deadline] requires 32 days
         -- Separator --
        [Requirments] requires 5 days
        [Risk assement] requires 5 days
        Then [Design] requires 1 week
        Then [Arcitecture] requires 1 week
        [Implimentation] requires 15 day
        [Implimentation] starts at [Design]'s end
        Then [Testing] requires 4 days
        Then [Review] requires 1 days
        mondays are coloured in Lightblue
        wednesdays are coloured in lightBlue
        @endgantt
      ```
    <\p2>
  </body>
</html>

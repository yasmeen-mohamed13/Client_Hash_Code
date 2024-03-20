This project consists of two parts:
1) Dispatcher: This part extracts data from work item pages and filters it to select work items with WI5 type only. The filtered data is then loaded into a queue in the orchestrator.
2) Performer: This component navigates to each item in the queue, extracts the ClientID,ClientName,ClientCountry. after that go to Hash Generator and Generae the security code.
   After that it take the security code and update this item Making the status Completed

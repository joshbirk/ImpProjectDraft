#Step 8: Use Process Builder to Chatter Fridge data

Finally, let's add some finesse to our application by using Process Builder to drive a Chatter conversation based on the incoming readings which create the case.


##Create a new Process Builder
1. Go to Setup
2. Go to Create | Workflows & Approvals | Process Builder
3. Click "New"
4. Name the new Process "Update Case for Smart Fridge"
5. Click "Add Object" and for "Find an Object" select "Case"
6. Leave the process at "only when a record is created"
7. Click "Add Criteria" and name it "Related to Smart Fridge"
8. Under set conditions, click "Find a Field".
9. Use field selector to find "Related Fridge" and then "DeviceId"
10. Under "Operator" select "Is Null"
11. Leave "Boolean" and "False"
12. Click "Save"
13. Under "Immediate Actions" next to the new criteria, click "Add Action"
14. Under Action Type, select "Post to Chatter"
15. Under Action name, type "Post Smart Fridge Data"
16. Under "Post To", select "This Record"
17. In the message section, type a message using the merge field lookup which reads something like "This case is related to Smart Fridge {![Case].Related_Fridge__c.DeviceId__c}.  It was recorded at a temperature of {![Case].Related_Fridge__c.Temperature__c}, humidity of {![Case].Related_Fridge__c.Temperature__c}{![Case].Related_Fridge__c.Humidity__c} and the door with a status of {![Case].Related_Fridge__c.Door__c}."
18. Click Save
19. Click "Activate"

Now whenever a case is created that has a related Smart Fridge, the important data about that fridge will be accessible right from the case's chatter feed.

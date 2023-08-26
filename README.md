# Looker Studio
The following is an example of a case I worked on before for a client that needed to see results regarding their Paid Marketing data.

**Because of confidentiality, I will not display the client's brand.**

## Case: Motorsports Championship

This client wanted a report that showed the performance of each one of their channels (Google and Meta Ads). The final product is the following, but I'll explain step by step how I reached the solution:

![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/ea798aae-7128-415c-b4d2-7b504d6c86cf)

1) First, we needed to identify where to get the data. For Google Ads we used the native connector and for Meta Ads we used Supermetrics, which is a tool that allows us to retrieve data from this source in a daily manner.
   
2) As we can see in the dashboard, there are a few calculated fields. This was necessary because the Performance Media Agency's business model is based on the Revenue obtained. So for this, I created some calculated fields like the following:

 ![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/42791c92-7bdf-4141-88e6-8cde0bc5dcb5)

 ![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/d3973b0e-339d-4d81-9a95-396e857704ee)

3) Also, below each channel, you can see there's an option to filter the results based on the different events the championship has. We detected that for each event, the client had multiple campaigns to target different markets. So to group them all under one name, first we did a little data cleanup, assigning a numeric ID to each event, and then I created the following query:

![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/a6c6243a-6dbd-435d-a1e6-12a18f41d770)

This allowed us to properly identify each event.

-> Following these steps, we achieved the Dashboard shared in the 1st picture. Which had no visuals, but had the numbers that the client needed to report results internally.

After this, proactively I created other pages inside the report, so they could have some visuals that helped them assess quickly the performance of each one of their channels and events.

![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/da7ac4f0-4827-40fc-a9be-c336e290d998)

Finally, another report was created to see the performance of their premium products (that's why we used other colors according to their Branding guidelines). 
In this case, I'm showing another tab of the report which helped the client assess in one view:

-Paid channel's share.
-Conversions and assistance in a Data-driven model (using GA4 source)
-Market share
-Traffic and Awareness metrics

![image](https://github.com/andreszetaeme/Looker_Studio/assets/104032549/237e9efc-6084-43f8-a397-ac616bb6db6e)




# fb-social-network
Social Network Using Force Directed Layout

The aim of the project was to visualize my social network, and find clusters on basis of connections. To accomplished the task, I wrote a python based web crawler using PhantomJS and Selenium to crawl friends&rsquo; list on Facebook (as Graph API restricts a number of results substantially). The data so obtained was then used to draw a graph by modeling people as charges and connection between them as spring. The modeling of charge and spring brought together the clusters which were closely connected and thus provided clusters without any other attributes. The clusters obtained once the people (charges) are similar despite their random initialization. Closely looking at the clusters, we find that there are clusters within clusters. Also, the people lying between two clusters are usually common to both of the clusters.

You may check the visualization in the link given above.
  

# Twitter_Social_Network-
For this project, I constructed a social network based on Twitter relationships. The construction of a social network based on Twitter relationships involves mapping the relationships between users on the platform into a graph structure. In this graph, each node represents a user and the links between nodes represent the relationships between users, such as following relationships.

Graph metrics are mathematical measurements that describe certain aspects of the network structure and can provide insights into the overall organization of the network. Some graph metrics used in the network analysis include degree distribution, clustering coefficient, diameter, closeness, betweenness, density, and metric closure.


Data Collection

Obtained data through Twitter scraping. To start web crawling, applied for a Twitter Developer account and once it was approved, created a new project called "Friendship Network" within the developer account. Additionally, received the necessary credentials, including the consumer key, consumer secret key, access token, and access secret token.

For the scraping process, we integrated the keys into our code and wrote a script to retrieve a user and their friends. This was achieved by utilizing the Tweepy library.

The Tweepy library, which is open source and written in Python, provides an effortless method for accessing the Twitter API using Python.

Following are the Tweepy functionalities that we used: ● OAuth: Tweepy handles all the complexities involved in using OAuth authentication required by the Twitter API, making it a convenient option for developers. It includes an OAuthHandler class that can be utilized to set the necessary credentials for all API calls. ● The API class: The API class in Tweepy provides access to various endpoints of the Twitter API through its many methods. These methods allow developers to utilize the full range of functionality offered by the Twitter API. Additionally, the API class includes specific methods such as get_user() and friends() for retrieving information about the user and its followings, respectively.

With this, retrieved the following of a user and stored it in a CSV file. A total of 121 following user details were retrieved from the API call.


Data Visualization

To visualize the data, we utilized the in-built Python library "Networkx". Including the user node and 121 following users there are a total of 122 nodes. The data was represented as a network graph, with the user and its followings represented as nodes and their relationships depicted as edges.


Network Measures
The degree distribution of a network is a measure of the number of connections or edges each node in the network has.

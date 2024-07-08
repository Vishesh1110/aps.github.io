# Youtube


## Course Information

* Course Name: Algorithmic Problem Solving
* Course Code: 23ECSE309
* Course Instructor: Prakash Hegade

## Personal Information

* Name: Vishesh Singh
* USN: 01FE21BCI036
* University: KLE Technological University, Hubballi


* * *


#### Note:
This page hosts:

* [Introduction](#introduction)
* [Why Video Streaming](#why-video-streaming)
* [Objectives](#objectives)
* [Business Cases Identified](#business-cases-identified)
* [References](#references)



## Introduction

<img width="800" alt="yt_banner" src="https://github.com/Vishesh1110/aps_portfolio/assets/79099604/c92686da-d21a-463d-bcbb-c146451da81f">

Welcome to my portfolio on YouTube and other video streaming platforms where I analysed the different data strutures and algorithms used in different operations and features provided by these platforms. I have analysed the algorithms on basis of the knowledge I get from the Algorithmic Problem Solving(APS) course taught at KLE Technological University. During this course, I explored the various algorithms, their time and space analysis and their other alternatives for optimization. This portfolio is a showcase of the learnings through various business cases each highlighting a different aspect of algorithmic problem solving.


## Why Video Streaming
YouTube is an American online video sharing platform owned by Google. Accessible worldwide. YouTube was launched on February 14, 2005, by Steve Chen, Chad Hurley, and Jawed Karim, three former employees of PayPal. Headquartered in San Bruno, California, United States, it is the second most visited website in the world. Its use advanced use data structures and algorithms for content creation, user specific recommendation is what attracted me towards it. YouTube's extensive ecosystem, including content creation, user interaction and live streaming provides a comprehensive case study.


## Objectives
* Analyze the different business cases which which has algorithmic problem solving approach for its application.
* Showcase different algorithms and data structures learnt in APS course.
* Illustrate how algorithmic problem solving can be applied to optimize and enhance various aspects of Video Streaming.
* Provide a clear understanding of algorithms and data structures used.



## Business Cases Identified


**1. Autocomplete while searching**

<img width="800" alt="yt_search" src="https://github.com/Vishesh1110/aps.github.io/assets/79099604/ca18eeaa-a8d4-4ccd-bf50-d6d4b708b518">

***Use Case***
Users should get the suggestions of their search query while after each typed character especially when the search query is big. Tries can be helpful for autocomplete functionality. They can efficiently store and retrieve strings based on prefixes, allowing YouTube to suggest completions as users type.


***Benefit***
Improved user experience and alllows fast and efficient searching.

***Algorithms***
* Tries: Tree data structure
  * Time Complexity: O(len) for insertion, deletion, and lookup operations, where len is the length of the key (typically a word)
  * Space Complexity: O(ALPHABET_SIZE * len) where ALPHABET_SIZE is the number of possible characters and len is the length of the key.

[Code for Tries](){:target="_blank"}

***Time and Space Complexity***
* Time Complexity: O(len) for insertion, deletion, and lookup operations, where len is the length of the key (typically a word)
* Space Complexity: O(ALPHABET_SIZE * len) where ALPHABET_SIZE is the number of possible characters and len is the length of the key.


**2. Add to Queue**

***Use Case***
Users can add a video of their choice in queue wihtout searching and playing it repeatedly. 

***Algorithms***
A Queue follows the principle of “First in, First out” (FIFO), where the first element added to the queue is the first one to be removed. For this paritcular use case the enqueue operation of queue wil be used.

<img width="750" alt="queue" src="https://github.com/Kingsman44/aps-portfolio.github.io/assets/79099604/5a6c677e-d446-432d-9b31-20be069740d7">

***Time and Space Complexity***
* Time Complexity: O(1), 
* Space Complexity: O(N), N: number of videos added

[Code for Queues](){:target="_blank"}

**3. Play in a Queue**

***Use Case***
Users can play a set of videos of their choice in queue wihtout searching and playing them repeatedly. 

***Algorithms***
* Queue Data Structure: A Queue Data Structure is a fundamental concept in computer science used for storing and managing data in a specific order. It follows the principle of “First in, First out” (FIFO), where the first element added to the queue is the first one to be removed. Queues are commonly used in various algorithms and applications for their simplicity and efficiency in managing data flow.

<img width="700" alt="queue" src="https://github.com/Kingsman44/aps-portfolio.github.io/assets/79099604/5a6c677e-d446-432d-9b31-20be069740d7">

***Time and Space Complexity***
* Time Complexity: O(1), 
* Space Complexity: O(N), N: number of videos in the playlist

[Code for Queues](){:target="_blank"}

**4. Create playlist**

***Use Case***
Users/Channel Owners can create a separate playlist for the different content in different domains published by them.

***Benefit***
Better content segregation.

***Algorithms***
* Doubly Ended Queue: Double Ended Queues are basically an implementation of the data structure double-ended queue. A queue data structure allows insertion only at the end and deletion from the front. This is like a queue in real life, wherein people are removed from the front and added at the back. Double-ended queues are a special case of queues where insertion and deletion operations are possible at both the ends.

***Time and Space Complexity***
* Accessing Elements- O(1)
* Insertion or removal of elements- O(N)
* Insertion or removal of elements at start or end- O(1)


[Code for deque](){:target="_blank"}


**5. YouTube Shorts Scrolling**

***Use Case***
Scrolling short form video content to get informed or entertained in a matter of seconds.

***Algorithms***
* Linked List: A linked list is a linear data structure that consists of a series of nodes connected by pointers. Each node contains data and a reference to the next node in the list. Unlike arrays, linked lists allow for efficient insertion or removal of elements from any position in the list, as the nodes are not stored contiguously in memory.
  
<img width="700" alt="sll" src="https://github.com/Vishesh1110/aps_portfolio/assets/79099604/1a20b10e-6494-4017-ac21-170fa3df2f8a">

***Time and Space Complexity***
* Adding an element: O(1) (best case when added at the head), O(N) (worst case when added at the end)

[Code for Linked List](){:target="_blank"}


**6. Live Location Services**

***Use Case***
* YouTube uses the Google Maps Services whihc internally uses the KD-Trees to efficiently store and query geotagged content (posts, stories) based on proximity to a user's location, enhancing the user experience by surfacing location-relevant content.

***Benefit***
* Proof of Authentication of the content uploaded.

***Algorithms***
KD-Tree: Divide and conquer, Tree data structure

***Time and Space Complexity***
Time Complexity: O(logn) on average for insertion and search operations (tree is balanced), O(n) in the worst case (tree is unbalanced), where n is the number of points in the tree.
Space Complexity: O(n) where n is the number of points stored in the tree.

[Code for KD Tress](){:target="_blank"}


**7. Live Premiering and Notifying**

***Use Case***
Binary Search Trees are employed to manage and search scheduled events and reminders within Google’s notification systems. BSTs facilitate efficient insertion, deletion, and retrieval operations based on event timestamps.

***Algorithms***
* Binary Search Tree: Binary search tree follows all properties of binary tree and its left child contains values less than the parent node and the right child contains values greater than the parent node. This hierarchical structure allows for efficient Searching, Insertion, and Deletion operations on the data stored in the tree.

***Time and Space Complexity***
* Time Complexity: O(logn) on average for insertion, deletion and search operations, O(n) in the worst case, where n is the number of nodes in the tree.
* Space Complexity: O(n) where n is the number of nodes in the tree.

[Code for Binary_Search_Tree](){:target="_blank"}


**8. Sort Videos based on Viewership**

***Use Case***
Users can get to know their creators or celebs in a much better way checking out their most viewed/least viewed content

***Benefit***
Enhanced user/creator interaction.

***Algorithms***
* Merge Sort: Merge sort is a sorting algorithm that follows the divide-and-conquer approach. It works by recursively dividing the input array into smaller subarrays and sorting those subarrays then merging them back together to obtain the sorted array.

***Time and Space Complexity***
Time Complexity: O(n logn)
Space Complexity: O(n), Additional space is required for the temporary array used during merging.

[Code for Merge_Sort](){:target="_blank"}


**9. Video Quality Adjustment**

***Use Case***
Users can adjust the video quality according to the network service strength available in thst area.

***Benefit***
Users can view their content even when there is poor network.

***Algorithms***
* Huffman Coding: Huffman Coding is a technique of compressing data to reduce its size without losing any of the details. It was first developed by David Huffman. Huffman Coding is generally useful to compress the data in which there are frequently occuring characters.


***Time and Space Complexity***
The time complexity for encoding each unique character based on its frequency is O(nlog n).
Extracting minimum frequency from the priority queue takes place 2*(n-1) times and its complexity is O(log n). Thus the overall complexity is O(nlog n).


[Code for Huffman_Coding](){:target="_blank"}


**10. Video/Community Posts Ranking**

***Use Case***
Better video recommendation can keep the user engaging and will help in retention of the user for a longer time, so the posts/videos are assigned a priority based on user interaction and its watch history.

***Algorithms***
* Each video/post is assigned a priority based on attributes such as recency, relevance to the user’s interests, and engagement metrics (like likes, comments and share). Priority queue can be used to manage and prioritize posts for each user’s feed.

***Time and Space Complexity***
* Time Complexity: O(logn), since it uses BST internally so its insertion and deletion takes log(n) time complexity
* Space Complexity: O(logn)

[Code for Priority_queue](){:target="_blank"}


**11. User Engagement Analysis**

***Use Case***
User engagement analysis requires the ability to collect and process large volumes of interaction data, such as views, likes, comments, and shares. Efficient data structures like hash maps and arrays are needed for quick data retrieval and aggregation. Additionally, machine learning algorithms are essential to derive insights and identify patterns in user behavior.

***Algorithms***
For user engagement analysis on a YouTube channel, data structures should efficiently store and retrieve large datasets, such as hash maps for quick access to engagement metrics, arrays for chronological data analysis, and graphs to visualize user interactions and trends. These structures must support real-time updates and scalability to handle increasing volumes of user engagement data.

***Time and Space Complexity***
* Time Complexity: O(V+E), V is the number of nodes or the number of interactions and E is the number of edges/cnnections
* Space Complexity: O(V)

[Code for graphs](){:target="_blank"}


**12. Reply to Comments**

***Use Case***
Replying to comments was introduced on YouTube to enhance user engagement and foster community interactions. It allows users to have meaningful conversations, provide feedback, and build connections directly within the platform. This feature helps create a more interactive and engaging environment for both content creators and viewers.


***Algorithms***
* To implement the reply-to-comments feature, data structures must support hierarchical relationships to nest replies under parent comments, provide efficient insertion and retrieval for real-time interaction, and ensure scalability to handle large volumes of comments and replies. Trees or nested linked lists are ideal for managing such hierarchical comment structures.

***Time and Space Complexity***
* Time Complexity: O(N), N is the total number of replies under a certain comment
* Space Complexity: O(N)

  
[Code for Trees](){:target="_blank"}


**14. User Data Safety/Security**

***Use Case***
User data safety and security require robust encryption methods to protect data in transit and at rest, secure data structures like encrypted databases for storing sensitive information, and access control mechanisms to ensure only authorized users can access or modify the data. Additionally, regular security audits and updates are essential to mitigate potential vulnerabilities.

***Algorithms***
Data structures for user data safety and security must support encryption to protect sensitive information, integrity checks to ensure data has not been tampered with, and access control features to manage permissions and prevent unauthorized access. Structures like secure hash tables and encrypted databases are essential for these purposes.


***Time and Space Complexity***
* Time Complexity: O(n) where n is the length of the input data.
* Space Complexity: O(1), fixed size output regardless of input.


[Code for Hashing](){:target="_blank"}


**15. Optimizing User Recommendations based on watch history**

***Use Case***
Optimizing user recommendations based on watch history requires the ability to store and efficiently access large amounts of user-specific data, process this data in real-time to identify patterns and preferences, and use machine learning algorithms to generate personalized content suggestions.

***Algorithms***
Lazy propagation can be used in optimizing user recommendations by deferring updates to user watch history and recommendation scores until they are explicitly needed. This approach reduces computational overhead and ensures that recommendations are generated using the most recent data without frequent recalculations.

***Time and Space Complexity***
* Time Complexity: O(N)

[Code for segment_tree](){:target="_blank"}

## References

* https://www.geeksforgeeks.org/ball-tree-and-kd-tree-algorithms/
* https://www.youtube.com/howyoutubeworks/our-commitments/sharing-revenue/#:~:text=YouTube's%20main%20source%20of%20revenue,%2C%20channel%20memberships%2C%20and%20merchandise.
* https://www.programiz.com/dsa/huffman-coding
* https://www.geeksforgeeks.org/lazy-propagation-in-segment-tree/
* https://cp-algorithms.com/data_structures/segment_tree.html


* * *

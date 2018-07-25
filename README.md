# Neo4j-assignment
Text and solution of an assignment (in the "Advanced Data Management" course) on Neo4j during my MSc in Computer Science and Engineering.

Preliminary activities
• After downloading and installing Neo4j, start Neo4j Desktop. Start a database, enable development mode and open the neo4jBrowser. You can now type and execute all Cypher commands.
• Create the Movie Graph database. You can get there by:
– Selecting Jump Into Code and then Movie Graph and Create Graph from
the main page of the browser
– Selecting Favorites → Sample Scripts → Example Graphs → Movie Graph from the left menu.
– DownloadingMovieGraph.cypfromAulaWebandimportingitinCypher). Execute all the creates, and observe the resulting graph.


Exercise 1: Cypher Queries
Creating your Movie Graph database instance. Then, for each of the following re- quests specify whether it can be expressed in Cypher. If yes, present and execute the corresponding statement. If no, or if some of your proposed statement raise some errors, discuss the issues and provide some motivations/possible alternatives.
For all the queries, examine the results in graph, textual, and tabular form.
1. Return a given person, retrieved by a condition on his/her name specified in the query.
2. Return the titles of the movies in which a given person, whose name is specified in the query, acted.
3. Return the persons interpreted a specific role, specified in the query, in any movie. Choose a role which is present in more than a movie or interpreted by more than one actor.
4. Return the pairs of actors that acted together in any movie.
5. Return the persons that are related somehow (by a relationship of any type) to Kevin Bacon, also displaying information about the relationship.
6. Return the persons that are related somehow (by a path of any length and of any type) to Kevin Bacon, limiting the result to the first 25 results. Rerun the query without the limit.
7. Return the pairs of nodes that are related by two different relationships.
8. Return the persons that directed a movie but did not wrote it.
9. Return the shortest path between any pair of movies traversing at least an edge of type acted in.
10. Return the three nodes with the highest number of relationships.
11. Return the length of the shortest path between two movies of your choice.
12. Return the movies that are at most 4 hops according to any relationship from The Matrix.
 
Exercise 2: Cypher Updates
On your Movie Graph database instance perform (if possible) the following updates and comment on their impact.
1. add a new movie of your choice and its actors
2. add a property to a movie or to an actor of your choice
3. add a property (with a default or computed value) to all the nodes with a certain characteristic of your choice (making used of the FOREACH statement).
Exercise 3: Modelling Additional Information
Extend the garph database with information about the books from which movies derive and corresponding author, publishing information, and significant differences between the book and the movie.
1. propose a way of representing this information in the property graph model
2. add at least an instance for each introduced concept
3. formulate in natural language and in Cypher a query involving the information you added.

# Cs429_project
Project Report: Movie review Search Application
Abstract:
The Movie review Search Application is a web-based platform developed using Visual Studio, aimed at facilitating users' searches for movie titles and providing relevant information. This project's primary goals were to create an intuitive user interface, implement efficient indexing and retrieval algorithms, and potentially enhance search accuracy through query processing techniques. Future plans include expanding the movie dataset, refining query processing capabilities, and improving the user experience with additional features.

Overview:
The Movie Search Application is built on a Flask framework, offering users a user-friendly interface for submitting movie title queries. Behind the scenes, an indexing system built with Scikit-Learn enables quick retrieval of relevant movie titles based on user input. The dataset used in the application includes diverse movies such as "The Challengers," "The Beekeeper," "Arcadian," "Civil War," "Monkey Man," "Dune 2," "Glass," "Madame Web," "Oppenheimer," and "Immaculate." Drawing inspiration from existing research in information retrieval and natural language processing, the system aims to deliver accurate and efficient search results to users, enhancing their movie-searching experience. The domains used are blogs and review sites such as "Rotten tomatoes", "Screen Rant" "Metacritic", "Hollywood Reporter", "Criticker"

Design:
The Movie Search Application is designed to provide users with an intuitive interface for submitting queries. User interactions involve inputting movie titles via the web interface. Optionally, queries undergo processing to enhance search accuracy, leveraging techniques such as spelling correction or query expansion. The system then queries the indexed data to retrieve relevant movie titles with the url, presenting them to the user through the web interface. This iterative process ensures a seamless user experience, with the system adapting to user inputs to deliver tailored search results.

Architecture:
The architecture of the Movie Search Application consists of several interconnected components. At its core lies the Flask web application, which serves as the primary user interface. This application communicates with the indexing system, which constructs and maintains an inverted index of movie titles and metadata. Optionally, a query processing module may be integrated into the indexing system to enhance search accuracy. The system's implementation adheres to software design best practices, promoting modularity, extensibility, and scalability.

Operation:
Operating the Movie Search Application is straightforward, they can launch the Flask application by executing the app.py script. Upon launching the application, users can access the web interface via a browser and input movie titles to initiate searches. The application efficiently handles user queries, retrieving relevant search results and presenting them clearly.

Conclusion:
In conclusion, the Movie Search Application represents a significant advancement in information retrieval and user interface design. Initial testing has shown the application's ability to index and retrieve movie titles efficiently. Further development is needed to fully implement query processing features and enhance search accuracy. With continued refinement and expansion, the application has the potential to become a valuable resource for movie enthusiasts seeking comprehensive movie information.

Data Sources:
The primary data source for the Movie Search Application is the IMDb dataset, providing comprehensive information on various movies. This dataset is publicly available and can be accessed through the IMDb website or third-party repositories.

Test Cases:
The Movie Search Application undergoes rigorous testing using the PyTest framework. Test coverage includes Flask routes, indexing functionality, and query processing (if implemented). A robust testing framework ensures the application's reliability and stability across different scenarios and usage patterns.

Source Code:
The Movie Search Application's source code is hosted on GitHub, offering transparency and accessibility. The repository includes detailed documentation, code listings, usage instructions, and dependencies. Open availability of the source code enables collaboration and contributions from developers to enhance the project further.

Bibliography:
Salton, G., Wong, A., & Yang, C. S. (1975). A vector space model for information retrieval. Communications of the ACM, 18(11), 613-620.
Manning, C. D., Raghavan, P., & Schütze, H. (2008). Introduction to Information Retrieval. Cambridge University Press.
Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825-2830.
Grus, J. (2015). Data Science from Scratch: First Principles with Python. O'Reilly Media.
Flask Documentation: [https://flask.palletsprojects.com/]
NLTK Documentation: [https://www.nltk.org/]

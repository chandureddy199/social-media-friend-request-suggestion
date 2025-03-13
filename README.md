# social-media-friend-request-suggestion
README

This project is a comprehensive simulation of a social networking system implemented in C, designed to demonstrate key programming concepts such as structures, arrays, string manipulation, and basic algorithms for data management and user interactions.

At its core, the project manages user profiles where each user is represented by a structure containing fields for the user's name, a list of interests, friend requests, and existing friends. The program supports fundamental operations like creating a new user, sending and processing friend requests, and updating user profiles without losing previously saved data. In particular, the mechanism for updating interests is thoughtfully designed to append new interests to the existing list rather than overwriting them. This feature helps maintain historical data about user preferences while allowing dynamic updates.

The application features a menu-driven interface that guides users through various functionalities. Users can add their profiles by entering their name and a set of interests, which are stored in fixed-size arrays. The program then offers friend suggestion capabilities based on two criteria: mutual interests and friend-of-a-friend relationships. The mutual interests functionality compares the interests of different users to find overlapping areas, while the friend-of-a-friend approach leverages the network structure to introduce connections beyond immediate acquaintances.

Friend requests are managed with care, allowing users to send, accept, or reject connection requests. When a friend request is accepted, the system automatically updates both users' friend lists, ensuring consistency across the network. The use of arrays for storing friend connections and requests, along with functions that perform checks for existing friendships or pending requests, illustrates essential aspects of data validation and memory management in C.

Throughout the code, error handling and boundary checking are implemented to ensure that operations such as adding new interests or users do not exceed predefined limits. This prevents common issues like buffer overflows and ensures that the application remains stable under different scenarios.

Overall, this project serves as an educational tool by simulating real-world social network functionalities in a controlled environment. It not only reinforces the understanding of data structures and algorithms in C but also provides a practical example of how a simple social network can be built from the ground up, making it an excellent starting point for further exploration and expansion into more complex systems.


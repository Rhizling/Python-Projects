# Python-Projects
Projects that I have worked on while expanding my knowledge on the python language and its packages.

Rock Paper Scissors Game:

This project incorporated fundamental and intermediate python syntax and logic in order to create a fake "AI" (mainly just the illusion of an AI) which challenges the user to the ultimate game of Rock Paper Scissors. The code incorporates the timer package and a GUI which displays a win, loss, or a draw at the end of each round. The GUI incorporates the tkinter and pillow package along with the ImageTk and Image modules in order to display PhotoImage objects in the user's window. The number of rounds are determined by the user and the images displayed were found from the internet.

Malaria-infected Cells identification Model:

This model was created in google colab through the guidance of an organization known as BigTh!nk AI and involved following the stages of training a model to analyze processed 27,558 200x200 pixel images from New York City hospitals and identifying malaria infection in blood cells. To accomplish this, the data had to be split into separate training/testing sets and optimized after the use of keras neural networks and activation functions with a binomial sigmoid output. A maximum of 5 epochs were used during the training phase with the model classifying each blood cell as either a true positive, true negative, false positive, and false negative - the accumulated percentages of each being displayed in a confusion matrix.

Password Manager Application:

This application is still technically a work-in-progress as there are additional nuances in the Tkinter and Pickle packages that would need to be implemented. However, the base framework is present as it is intended to provide an easier method for users to store personal password and username data across a wide variety of sites. As the credentials for these sites can only stack up, the program is intended to lock all these passwords under one singular password that the user would have to remember. Furthermore, the user would be able to add and remove sites in the sites page freely once authorization is granted in the program. To store this data more adequately, a Site object is created and is intended to later be pickled so that the program can permanenty store the user's private data. As this application is meant to be quite large, there are multiple areas which would need additional work. In the future, it is likley that implementing a sql database may provide more effective encapsulation and long-term practicality in the future. However, at the moment, I am stepping away from this project to work on different skills other than GUI implementation.

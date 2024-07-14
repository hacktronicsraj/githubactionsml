This is a GitHub actions project that uses CML to check weather the made changes or the added features to a machine learning model are affecting the total outcome of the model in a positive or negative way,

we do this by creating a GitHub actions workflow whenever a pull request is created the CML pipeline is run and that pipeline checks weather the new feature improves the accuracy, specificity, and sensitivity of the model by giving us the differences between before and after the pull request.

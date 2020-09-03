- The python jypyter notebook initially contains a cell that has all the important librarires to be imported
- It then have all the necessary functions that are required to train a model and do experiments
- Some of these functions are create_model, compile_model, fit_model, plot_graph, plot_confusion matrix, k-fold_validation, data_augmented_files etc
- After that we have a practical example of the final best selected model (InceptionV3) and all the outputs have been sved to show the working
- There is a method called predict_test_set() which can then finally be used to predict images.
	You need to pass an array of images into it and then get the labels array in return.
	A practical example has been done at the very last cell of this notebook
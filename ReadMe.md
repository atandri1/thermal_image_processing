Thermal Image Processing Code

These two scripts are designed to process the thermal images taken by the Bosch GTC 400C Thermal camera. 
In order to work, the images must be taken in the black and white setting. Maximum and minimum values should be set manually and updated in the script. 

`automated_thermal_processing` is a fully automated method that will take a folder of images (theoretically from one experiment) and sample the temperature at the same point in all pictures. Additionally, it uses text recognition via pyTesseract to extract the timestamps from these images. 

`thermal_processing_click_coord` is a semi-automated process: the user is prompted with each image in a folder, and clicks the point in each image where measurement is desired. 

# Palmprint Authentication System - Execution Guide

1. Environment Setup:
Ensure you have Python (3.x recommended) installed.

2. Install Dependencies:
Run the command `pip install opencv-python Pillow tensorflow scikit-learn numpy matplotlib` to install required packages.

3. Run the Application:
Execute the main code file `palmprint_authentication_system.py`. (Please make replacements in code with customized file locations by downloading the provided dataset 'Palmimages.zip')

4. Registration:
Click "Register" to start palm registration. Follow on-screen instructions for capturing palm images.

5. User Verification:
Click the "Verify" button to authenticate a user. Opt for either "Upload Image" to use a provided image ('testimg.JPG') or choose to "Capture Image" by using any palm image of your choice.

6. Unregistration:
Click "Unregister" to remove a registered user. Enter the user label when prompted.

7. Note:
- Ensure the `model.h5` file is in the specified path.
- User palmprints are stored in `C:/Users/chait/Downloads/Bio_Project/Palmimages/`. (however, you can specify your decide location to save files when executed)

8. Additional Info:
- Data augmentation and learning rate scheduling are applied during training.
- The system uses a CNN model for palm authentication.

9. Author:
Chaitanya Lakshmi Chava, Shravan Sailada, Vathsalya Pakalpati

10. Date:
12/12/2023

11. Customization:
Customize paths and parameters as needed in the code.

12. Feedback:
For issues or improvements, contact chavachaitanyalakshmi@gmail.com

13. Acknowledgments:
Acknowledgments to OpenCV, TensorFlow, and Tkinter.

14. Project Information:
This project is for educational purposes only. Developed under the guidance of Professor Vir Virander Poha at Syracuse Univeristy

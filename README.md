# Stegnography
Securing Secrets in Pixels - Encrypt and Decrypt Messages within Images
This code serves as a basic illustration of steganography and may lack the security and reliability needed for real-world applications. For strong message encryption, it is essential to employ advanced and secure techniques. Moreover, the successful execution of this code depends on the correct configuration of your Python environment and the installation of necessary libraries.

# How does it work?
An image is loaded from the file 'butterfly.png,' and the user is prompted to input a secret message and a password. Two dictionaries are created to map characters to their corresponding ASCII values. The process of hiding the message within the image, known as encryption, involves traversing the image and replacing its RGB values with ASCII values from the message. The resulting image is saved as 'EncryptedButterfly.jpg,' and it can be opened for viewing. To decrypt the message, the user must provide a password, and if it matches the one used during encryption, the ASCII values in the image are converted back into characters to reveal the hidden message. An 'Invalid password!' message is displayed if the password is incorrect.

# Limitations observed
1. Security Concerns: Since it's a simple steganography technique that hides the message in the image, it is not suitable for secure communications
2. Dependence on OpenCV as the code relies on the OpenCV library for image processing. If OpenCV is not installed or configured correctly, the code won't work.
3. No Support for Various Image Formats because the code specifically reads and writes images in a single format (e.g., PNG or JPEG). It doesn't handle various image formats.

# Future Modifications
1. Error Handling for Image Loading
2. User Guidance
3. Password Validation to implement strong password security practices

4. # Better techniques?
Improved techniques will be applied and updated on this page.

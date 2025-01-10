# LSB_IMAGE_STEGANOGRAPHY
This is a steganography project for secure data hiding and extraction within digital media files (images, audio, video) using techniques like Least Significant Bit (LSB) and encryption. Features include data confidentiality, seamless integration, and minimal impact on media quality. It is ideal for secure communication.

Name:Satya Ranjan Sahoo (24021D_092)
Date:20/11/2024
Description:Steganography

## CODE EXECUTION STEPS ##

Input:./a.out -e beautiful.bmp secret.txt stego.bmp
Output: Selected encoding
Read and validate encode arguments is a success
############# Started Encoding #############   
Open files is a successfully
width = 1024
height = 768
Check capacity is successfully
Copied BMP header successfully
Encoded magic string successfully
Encoded secret file extn size successfully
Encoded secret file extn successfully
Encoded secret file size successfully
Encoded secret file data successfully
Copied remaining data successfully
<--------Completed encoding-------->
Input:./a.out -d stego.bmp decode.txt
 Output: Selected decoding
 Read and validate decode arguments is a success
 ############### Started Decoding ##############
 Open files is a successfully
 Decoded magic string Successfully
 Decoded file extension size successfully
 Decoded Secret File Extension Succesfully 
 Decoded secret file size Successfully
 Decoded secret file data successfully
       <---------Completed decoding--------->
*/

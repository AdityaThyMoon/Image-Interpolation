# Project where I recreate image interpolation from scratch, as well as tried some other cool image processing techniques
### Some cool results below

# Einstein. This image's colour is intentionally downtuned
![image](https://github.com/user-attachments/assets/861ac508-2d8b-41af-8b8c-d0f4b46874c5)
After histogram equalization:
![einstein_equalized](https://github.com/user-attachments/assets/24999d91-aa09-4e6e-b72e-2194bfcc5412)

# Testing some filters

Negative filter
![cameraman_negative](https://github.com/user-attachments/assets/9bdcba2d-ca11-4850-b51f-ab9d8c136447)

Power filter
![cameraman_power](https://github.com/user-attachments/assets/db771bdb-0d25-4b37-a628-a1c7f6fbe843)

# Famous "Lenna" Image, purposely downtuned (so it could be fixed)
![lena_nearest_scratch](https://github.com/user-attachments/assets/f5644f5f-a026-4f9d-bc0b-ee7b7cb6e70a)

# Then I fixed it, using nearest neighbour, bilinear, and bicubic interpolation respectively:
### Note that the results vary minimally, but if you look carefully, you'll see the difference in quality

![lena_nearest_cv](https://github.com/user-attachments/assets/81e627c9-12e7-4ec0-9af1-9010ae9745ab)
![lena_bilinear_cv](https://github.com/user-attachments/assets/cd47f97b-33fc-48a8-b64a-d8d2a7659914)
![lena_bicubic_cv](https://github.com/user-attachments/assets/a44684b1-c475-43f8-ae39-ba0eefc8ff71)

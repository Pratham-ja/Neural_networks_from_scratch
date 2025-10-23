# Neural_networks_from_scratch

Inspired by Andrej Karpathy youtube videos in which he build neural networks from scratch 
Recently I watched youtube videos of Andrej Karpathy and found them very intuitive and inspired me to reproduce them watching those videos.

import base64

# Replace 'image.png' with your image file name
with open("C:\Users\Pratham\Pictures\Screenshots\Screenshot 2025-10-23 234754.png", "rb") as img_file:
    b64_string = base64.b64encode(img_file.read()).decode()

# This prints the Base64 string; it will be very long
print(f"![My Image](data:C:\Users\Pratham\Pictures\Screenshots\Screenshot 2025-10-23 234754.png;base64,{b64_string})")
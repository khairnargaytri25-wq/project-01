# project-01
print("hello this is my project"
)
my-first-repo/
├── hello.py
└── README.md
from PIL import Image
import matplotlib.pyplot as plt

# Open image (keep image in same folder)
image = Image.open("image.jpg")

# Show image
plt.imshow(image)
plt.axis("off")
plt.show()

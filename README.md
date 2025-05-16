# OpenCV OCR Text Detection (Ubuntu Adaptation)

🚀 Adapted from [Qengineering's Raspberry Pi OCR Project](https://github.com/Qengineering/OpenCV_OCR_Detect_Text.git) for Ubuntu systems.

⚠️ **Note:** This version is specifically modified to run on Ubuntu 18.04/20.04 or later, and **does not require a Raspberry Pi.**
## 📷 What It Does

This project uses OpenCV's deep learning `DB_TD500_resnet50.onnx` model to detect text in images.

## 🛠 Requirements

- Ubuntu 18.04/20.04+
- OpenCV ≥ 4.5 (built with DNN module)
- Code::Blocks IDE (or compile manually)
- CMake and g++ for builds

## 🧪 How to Use

1. Clone or download this repo  
2. Open `OpenCV_Detect_Text.cbp` in Code::Blocks  
3. Build and run the project  
4. Place your image in the same folder
5. change input image in project -> Set program's arguement and change your image path(eg: `img.jpg`)
6. Modify `main.cpp` to load your image (eg: `"my_image.jpg"`)  
7. Run and check output like `out.jpg`

## 🙌 Credits

- Original work: Qengineering ([GitHub](https://github.com/Qengineering))  
- Paper: [Scene Text Detection](https://arxiv.org/pdf/1507.05717.pdf)

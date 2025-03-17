📝 Extract Text From Image
📌 Overview
This project uses Tesseract OCR to extract text from images efficiently. It leverages image preprocessing techniques like grayscale conversion, thresholding, and noise removal to enhance text recognition accuracy. The extracted text is displayed as output, allowing further processing or storage.

🔹 Key Features
✔️ Loads and processes images for OCR
✔️ Converts images to grayscale to improve text visibility
✔️ Applies thresholding and noise removal to enhance accuracy
✔️ Uses Tesseract OCR to extract text from images
✔️ Supports multi-language text recognition
✔️ Outputs extracted text for further use or storage

🔹 Implementation Steps
1️⃣ Install Dependencies – Install Python libraries (pytesseract, opencv) and ensure Tesseract OCR is installed on the system.

2️⃣ Load Image – Read the image file and display it to ensure it's loaded correctly.

3️⃣ Preprocess Image – Convert the image to grayscale for better text detection.

4️⃣ Apply Image Enhancement – Use techniques like thresholding and noise removal to improve OCR accuracy.

5️⃣ Extract Text Using Tesseract – Pass the processed image to Tesseract OCR to extract text.

6️⃣ Display and Store the Extracted Text – The recognized text is printed and can be saved for further analysis.

🔹 Advantages of This Approach
✅ Works Offline – No internet required for text extraction.
✅ Supports Multiple Languages – Can extract text in different languages with language packs.
✅ Fast and Lightweight – Works efficiently on most systems.
✅ Customizable – Can add advanced preprocessing for improved accuracy

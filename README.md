# Optimuz
This repository contains the code for a GENAI-based project featuring a user interface that offers various accessibility options. It utilizes PADDLE OCR for optical character recognition and integrates the GEMINI AI chatbot for enhanced user interaction.





"We implemented the PaddleOCR model to extract text from images. While PaddleOCR excels at detecting horizontal text, we enhanced its performance on vertically aligned and lengthy text by fine-tuning several parameters:

use_angle_cls=True: Activates vertical alignment detection and rotation.
det_db_box_thresh=0.2: Lowers the detection threshold to improve text detection rates.
det_db_unclip_ratio=2.5: Increases the unclip ratio to capture more extensive text areas.
lang='en': Sets the language to English.
rec=False: Disables the recognition component.
det_limit_side_len=1536: Establishes a maximum side length for detected text.

<img src ="https://github.com/user-attachments/assets/f603e2b9-7401-4836-9d8f-3e469f5d460b" alt="Example Image" width="600" height="400">
![ocr_output_with_boxes2](https://github.com/user-attachments/assets/f603e2b9-7401-4836-9d8f-3e469f5d460b)





Ultimately, we extracted a JSON file from the output generated by the OCR model."


# 🕸️ Ascii_Art


This Python script converts an image into ASCII art. It reads an image file, processes it, and generates ASCII art based on the brightness of each pixel in the image.


## 🛠️ Main Technologies

- `Python 3.x`
  - `PIL`

## 🚦 Running the Project

1. Install Python from [python.org](https://www.python.org/downloads/).
2. Install Pillow library using `pip install Pillow`.
3. Save the provided script as a `.py` file.
4. Modify the `FILE_PATH` and `OUTPUT_PATH` variables in the script.
5. Open a terminal or command prompt.
6. Navigate to the directory containing the script by `cd Ascii_Art`.
7. Run the script using `python ascii_art.py`.

## How it Works

1. **🖼️ Image Input**: The script takes an image file as input. Ensure the file path is correctly specified.

2. **⏱️ Processing**: 
   - The image is opened and converted to grayscale using the Pillow library (`PIL`).
   - The size of the image is adjusted to a standard width of 80 pixels while maintaining the aspect ratio.
   - Each pixel's brightness is mapped to a corresponding ASCII character. Brighter pixels correspond to denser characters.

3. **🗺️ Character Mapping**:
   - A list of characters ranging from dark to light is used to represent the image. 
   - The brightness of each pixel determines which character from this list is used.

4. **🏋️‍♂️ Output**:
   - The generated ASCII art is saved into a text file with the specified output file path.

5. **Exception Handling**:
   - The script includes error handling to manage exceptions that may occur during image processing.


## 🐛 Current Bug

So far, I'm not really sure if there are any bugs. However, there might be some issues. I tested it out on my computer (Windows 10), and so far it looks good there.

## 🍿 Preview

`image : `

![Screenshot (60)](https://github.com/malik-l0l/Ascii_Art/assets/154656931/9e320222-d577-44e8-ae04-f70738a322ab)


`ascii_art : `

![Screenshot (59)](https://github.com/malik-l0l/Ascii_Art/assets/154656931/9b27bae9-3120-4c1c-93f4-646e8b92a011)


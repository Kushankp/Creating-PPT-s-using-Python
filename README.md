# PowerPoint Presentation Content Modification

This code allows you to modify the content of a PowerPoint presentation using the `pptx` library in Python.

## Functions
- `set_font(text_frame, font_file, font_size)`: This function sets the font style for the text in a PowerPoint slide.
- `add_content_to_slide(slide, content, font_file, font_size)`: This function adds content to a slide and applies the specified font style.

## Usage
1. Make sure you have the required Python packages installed (`pptx`).
2. Modify the code to specify the input file paths (`sample_slide1_input.txt`, `sample_slide2_input.txt`) and the font file path (`sample_font_file.ttf`).
3. Run the code to create a new PowerPoint presentation with the modified content.
4. The output presentation will be saved as `output.pptx` in the same directory.

## Dependencies
- `pptx`: Python library for creating and modifying PowerPoint (.pptx) files.

## Notes
- Make sure to have the required input files (`sample_slide1_input.txt`, `sample_slide2_input.txt`) and font file (`sample_font_file.ttf`) in the same directory as the code.
- Adjust the font size (`font_size`) as needed.
- You can customize the code further to suit your specific requirements.
- For more information, refer to the official documentation of the `pptx` library.


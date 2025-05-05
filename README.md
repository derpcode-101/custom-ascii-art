# ASCII Art Drawing Converter

An interactive web-based tool that converts your drawings into ASCII art with customizable settings.

## Features

- **Drawing Tools**: Pen for drawing and eraser for corrections
- **Customizable ASCII Conversion**: Adjust resolution and character sets
- **Background Preservation**: White background remains as spaces in the output
- **Copy to Clipboard**: Easy sharing of your ASCII creations

## How to Use

1. **Draw Your Image**: Use the pen tool to create your drawing on the canvas
2. **Customize Output**: Adjust the ASCII resolution slider and select your preferred character set
3. **Convert**: Click the "Convert to ASCII" button to transform your drawing
4. **Copy**: Use the "Copy ASCII Art" button to copy the result to your clipboard
5. **Paste & Share**: Paste your ASCII art into messages, documents, or social media

## Character Sets

The program offers multiple character density options:

- **Dense** (`@%#*+=-:. `): Good for smaller, detailed ASCII art
- **Detailed** (`$@B%8&WM#*oahkbdpqwmZO0QLCJUYXzcvunxrjft/\|()1{}[]?-_+~<>i!lI;:,"^'. `): Provides maximum detail with many brightness levels
- **Simple** (`@#$%?*+;:,. `): Cleaner look with fewer characters
- **Blocks** (`█▓▒░ `): Unicode block characters for a more graphical appearance

## Technical Details

The converter works by:

1. Dividing your drawing into a grid based on your selected resolution
2. Analyzing each cell to determine if it's part of your drawing or background
3. For non-background cells, calculating the average brightness
4. Mapping brightness values to characters from the selected character set
5. Assembling the characters into ASCII art that represents your drawing

## Tips for Better Results

- **Simple Drawings**: Start with simple shapes and lines for best results
- **Higher Resolution**: Increase the resolution slider for more detailed output
- **Character Set Selection**: Choose the character set that best suits your drawing style
- **Contrast**: Create drawings with good contrast for more defined ASCII output
- **Background**: The program automatically preserves white space, so you don't need to worry about the background

## Example Use Cases

- Create ASCII art signatures for emails
- Design text-based logos
- Make ASCII art for forums, comments, or text-only platforms
- Create old-school ASCII art for retro computing enthusiasts
- Design text-art for README files in code repositories

---
                               
                                                  
                #==+@                             
                =  @=%  %+=*                      
                =   @=#*+@ *#                     
                =@   @==   @=                     
                %=@   @%    =                     
                 #+         =                     
                  *#        =                     
                   =@      @+                     
                   @=      +@                     
                    #*    %+                      
                     =@  @=@                      
                     @+  +%                       
                      +@**                        
                      %=+                         
                       +@                         
                                                     
                                            

*This tool runs entirely in your browser and doesn't upload your drawings to any server.*

# Test_Case_Samples

1️⃣ **Accessibility testing on the [Golden Globes website](https://goldenglobes.com/)**. Some of the test cases were executed using WAVE tool - Chrome extentsion.

#### Test ID: 1 - Passed :white_check_mark:

**Test description**: The content of the website is visible when high contrast mode is turned on.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.
- The high contrast mode, in black, is turned on from your device's settings.

| Steps to reproduce:                                 | Expected result:                                                                         |
|-----------------------------------------------------|------------------------------------------------------------------------------------------|
| Navigate through the website in high contrast mode. | The content of the website is visible and automatically highlighted in white or yellow. :heavy_check_mark: |

________________________________________________________________________
#### Test ID: 2 - Passed :white_check_mark:

**Test description**: The website can be accessed using keyboard navigation. 

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                                                           | Expected result:                                                                                                                                                                                    |
|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Navigate through the website using the Tab key (forward), Tab+Shift keys (backwards), Enter/Spacebar (activate), Spacebar/Arrows (scroll) etc. | You can navigate through the website and activate the elements using the indicated keys. ✔️ |

__________________________________________________________________
#### Test ID: 3 - Failed ❌

**Test description**: The HTML code for the images on the website contains the "alt" attribute, providing a description of the image content for screen readers.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                                                                    | Expected result:                                                                                                                                            |
|------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Open developer tools for the first image, by right clicking on it and  then clicking "inspect" from the opened pop up. | Developer tools is open in the elements section,  showing the HTML code for the image.                                                                      |
| Look for the "alt" attribute in the image's HTML code.                                                                 | The "alt" attribute exists and it describes the image content clearly and concisely,  focusing on its function and meaning within the context of your page. ❌ |

_____________________________________________________________________
#### Test ID: 4 - Passed :white_check_mark:

**Test description**: The images on the website are provided with suitable, clear captions.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                                                                  | Expected result:                                                                                                                      |
|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Scroll down to the section "Golden Globe Fashion - The best looks and trends for the season" and click on "read me". | The chosen section opens in new page, showcasing different images of celebrities  on the red carpet, organized as an image carrousel. |
| Check that every image has clear captions, that accurately describe the image they accompany.                        | Every image has clear captions, that accurately describe the image they accompany. ✔️                                                    |

_____________________________________________________________
#### Test ID: 5 - Failed ❌

**Test description**: The elements on the page that currently have keyboard focus are provided with focus indicators.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                                                                  | Expected result:                                                                                                                     |
|----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| Navigate through the website using the Tab key (forward), Tab+Shift keys (backwards) and Enter/Spacebar (activate). | When an item is tabbed to, it has a visible "keyboard focus" - a visual indicator of the element that currently has keyboard focus. ❌  |

_____________________________________________________________________________
#### Test ID: 6 - Passed :white_check_mark:

**Test description**: The default keyboard navigation order is logical and intuitive.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                                                                                | Expected result:                                                                                                               |
|------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| Navigate through the website using the Tab key (forward), Tab+Shift keys (backwards) and Enter/Spacebar, Spacebar/Arrows (scroll). | The keyboard navigation order is logical and intuitive. It follows the visual flow of the page: left to right, top to bottom. ✔️  |

___________________________________________________________________________
#### Test ID: 7 - Failed ❌

**Test description**: All text is visible, checking color and size.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                        | Expected result:                                                                                      |
|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Navigate through the website and inspect the colors and sizes of the text. | All text is visible and easy to read.  Its color and size is suitable even for those with low vision. ❌ |

__________________________________________________________________________
#### Test ID: 8 - Failed ❌

**Test description**: All links are provided with text in the HTML code.

**Preconditions**: 
- The [url](https://goldenglobes.com/) is open in browser.

| Steps to reproduce:                                                 | Expected result:                                                                                                             |
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| Open WAVE tool from the Chrome extension and run it on the website. | After the evaluation, all links contain text in the HTML code, presenting the  function or purpose of the link to the user. ❌ |

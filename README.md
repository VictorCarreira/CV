# Lattes CV to LaTeX Resume Converter

This project converts a Lattes CV (Brazilian academic curriculum) into a formatted LaTeX resume using the "Twenty One Seconds Resume/CV" template.

## Project Structure

* **resume.tex:** The LaTeX template for the resume. This file is provided as a starting point and will be populated with the extracted Lattes CV data.
* **twentyonesecondcv.cls:** The custom LaTeX class file required for the "Twenty One Seconds Resume/CV" template. You need this file to compile the resume.
* **2024_06_29_acf33ffb82555b8284bcg.tex:** An alternative LaTeX file generated from the Lattes CV, likely using a different template.
* **Currículo do Sistema de Currículos Lattes (Victor Ribeiro Carreira).docx:** The Lattes CV data in Microsoft Word format.
* **Currículo do Sistema de Currículos Lattes (Victor Ribeiro Carreira).md:** The Lattes CV data in Markdown format. 

## Instructions

1. **Obtain the Lattes CV Data:**
   * Download the Lattes CV of the person you want to create a resume for, preferably in XML or JSON format. The provided `.docx` and `.md` files are for reference.

2. **Provide the Lattes CV Data:**
   * You'll need to provide the structured Lattes CV data to an AI language model capable of processing it (like ChatGPT or a custom script).  

3. **Populate "resume.tex":** 
   * The AI language model will map the data from the Lattes CV to the corresponding fields in the "resume.tex" template.
   * You will receive a modified "resume.tex" file containing Victor's CV information.

4. **Compile the LaTeX Resume:**
   * Make sure you have a LaTeX distribution installed (like TeX Live or MikTeX).
   * Compile the "resume.tex" file using a LaTeX compiler (like XeLaTeX). This will generate a PDF resume. 

## Customization

* **Profile Picture:** Replace `"image.png"` in `\profilepic{image.png}` with the filename of your profile picture.
* **Template Modifications:** You can further customize the "resume.tex" template to suit your needs. Refer to the template's documentation for available options.

## Notes

* The success of the data mapping depends on the accuracy and structure of the extracted Lattes CV data.
* You might need to manually adjust some parts of the generated "resume.tex" file for optimal formatting.

## Credits

* The "Twenty One Seconds Resume/CV" template is originally from [LaTeXTemplates.com](http://www.LaTeXTemplates.com) and maintained by Alessandro Trinca Tornidor. 
* The Lattes CV data belongs to Victor Ribeiro Carreira. 


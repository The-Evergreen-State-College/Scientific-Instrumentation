# How to add a new instrument

## Get image(s) of the instrument
1. Get a high-resolution image of the instrument from the internet or take a photo of it.
2. save the image(s) in: `assets/images` with the following naming convention:
   - Make-Model-InstrumentClass {.jpg, .png}
    - e.g. `Leica-M205-FCS-Microscope.jpg` , `TESCAN-Clara-SEM.jpg`
    

## Make a copy of the instrument template: Instrumentation/Instrument-Template.qmd
1. Copy the template file `/Instrumentation/Instrumentation_Template.qmd` to the '/Instrumentation' folder and rename it to: <Make>-<Model>-<InstrumentClass>.qmd>
   - <Make> = Manufacturer of the instrument
   - <Model> - Model of the instrument
   - <InstrumentClass> = Class of the instrument (e.g. Microscope, SEM, etc.)
2. Fill in the 'Title'
3. Add image to the top of the page.
   - replace `![](/assets/images/<image> "Instrument Name"){fig-align="left" width=300}` with the image you saved in the previous step.
   - e.g. `![](/assets/images/Leica-M205-FCS-Microscope.jpg "Leica M205 FCA Microscope"){fig-align="left" width=300}`
4. Fill in the rest of the page.

## Add the instrument to the index page: index.qmd
1. This is the gallery page. Add the image to the gallery in the meta-category for the instrument class.

## Add instrument to the meta-category page: MetaCategory/<MetaCategory>.qmd
1. This is the page that lists all the instruments in the meta-category. Add the image of instrument to the list of instruments in the meta-category.

## Add instrument to the _quarto.yml file
1. This is the file that controls the navigation of the website. Add the instrument to the list of instruments.

## Copy SI-Table-Schema.qmd for the instrument
1. Copy the SI-Table-Schema.qmd file to the 'Instrumentation' folder and rename it to: SI-Table-Make-Model.qmd

## Create Github issue that is the digital logbook entry for the instrument
1. Add the Digital logbook to the logbook index page: Instrumentation/Logbook.qmd

## Quarto must now be rendered

## Commit local project

## Push to remote repository or create a GitHub pull request
1. Push the changes to the remote repository or create a pull request for the changes to be merged into the main branch.

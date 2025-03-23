# Checklist

Create BOM and work from there so you don't go back and forth with components. Download from mouser models and add to
library.

## Schematic design

- [ ] Setup
    - [ ] Set grid
    - [ ] Page settings (TODO revise date on date of release)
    - [ ] Create variables that will be used throughout the project (project name, date...)
    - [ ] Add libraries/components
- [ ] Symbols
    - [ ] Add symbols to the sheet
    - [ ] Create symbols if needed
    - [ ] Add values to symbols (Component values)
    - [ ] Add mechanical symbols (mounting holes)
- [ ] Arrange, annotate, associate
    - [ ] Arrange symbols in functional blocks
    - [ ] Annotate symbols
    - [ ] Associate with footprints
- [ ] Wire
    - [ ] Signals
    - [ ] Power (PWR_FLAG)
- [ ] Nets
    - [ ] Set net names (if not automatically assigned)
- [ ] Electrical Rules Check
    - [ ] Run ERC
    - [ ] Fix errors
    - [ ] Repeat ERC
- [ ] Comments
    - [ ] Add text information (group component in boxes, add comments)
    - [ ] Add graphics

## Layout design

- [ ] Setup
    - [ ] Set grid
    - [ ] Set design rules (check manufacturer for constraints for minimum values)
    - [ ] Import footprints from schematic
    - [ ] Assign 3D models if they're not already assigned
- [ ] Outline and constrains
    - [ ] Define size and shape (Edge.Cuts layer)
    - [ ] Define cutouts
- [ ] Footprints
    - [ ] Place components on board
    - [ ] Arrange user interface components
    - [ ] Arrange in functional blocks
    - [ ] Complete placement
- [ ] Route
    - [ ] Critical traces
    - [ ] Power
    - [ ] Copper fills
    - [ ] Everything else
- [ ] Silkscreen (F.Silkscreen and B.Silkscreen layers)
    - [ ] Add text information (reference designators, functionality text (boost, gain, bright...))
    - [ ] Add graphics (name, personal logo/name, version)
- [ ] Design rules check
    - [ ] Run DRC
    - [ ] Fix errors
    - [ ] Repeat DRC
- [ ] Export & Manufacture
    - [ ] Create Gerber files
    - [ ] Verify Gerber files
    - [ ] Upload Gerber files to manufacturer

## Enclosure design

- [ ] Make an enclosure
- [ ] 3D print and test

## Definition of Done

Write down DoD as a guide so you know when you've finished this project for good.
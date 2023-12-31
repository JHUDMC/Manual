# Circulating Resource Management

## Circulation Room

## Getting Equipment Online

## Inventory

The DMC circulates almost 1,000 individual items, many of which are complicated kits with many parts. Inventory should be completed every year (either all at once when the DMC is closed or on a rolling basis, one category at a time). 

### Prior to Inventory
- Make sure that every checked-out resource is returned and present in the lab and cage!!
- Export list of items from inventory system into a spreadsheet. Include only items that are online (either in maintenance or fully operational - lost or deaccessioned items are not included). [Use the inventory software tool](https://github.com/JHUDMC/LibCal-API-Experiments/tree/455cb978adc1c5bc4ef4cd564f3fed802d6af9d2/Inventory) to create this list.

- Required information for each individual resource:
  - Barcode
  - Name
  - Components
  - Value
  - Condition Notes
  - Serial Number (not all items will have)
  - Manufacturer/Model (not all items will have)
  - Asset Tag (item location within the cage)

- Create a [mail merge document](https://support.microsoft.com/en-us/topic/how-to-use-the-mail-merge-feature-in-word-to-create-and-to-print-form-letters-that-use-the-data-from-an-excel-worksheet-d8709e29-c106-2348-7e38-13eecc338679) that generates an individual sheet for each resource with information pulled from the spreadsheet. You can use this [template](media/Inventory%20Template.docx) (the words in ``« »`` correspond to merge fields from the spreadsheet).
- Print every single sheet (lots of paper!) The Phase 1 process is entirely physical and is digitized after all physical items are inspected. You may want to skip the invidiual sheets for single-component simple items like audio adapters -- simply print a separate spreadsheet to mark them off as you complete them.
- Sort the sheets into broad category folders, keeping identical items/those that are part of the same "Main Item Records" clipped together.

### Phase 1: Physical Inspection/Cleaning
- The DMC should be closed to patrons during inventory with Pro Staff and Student Staff present for the process. Clear out some space on lab tables to spread out.
- This phase of inventory is mostly for cleaning and checking to make sure all items are present in each kit. Unless there is a condition note/the item looks to be broken, do not spend time thoroughly testing the functionality of each item.
- Divide up categories, each staffer taking one at a time. Pull the items from the shelves and note their locations.
- Go through the sheet for each item, checking for the presence of all listed components and making notes for corrections to component list format, contents, etc. You don't need to add the specific information at this time (for example, adding a missing value may take some research), but indicate that it needs attention. Other notes for corrections or actions that need to be taken can be written on the sheet as well. Initial the sheet when complete.
- Every component should be cleaned with appropriate cleaning materials, and the inside of each bag/case should also be cleaned if needed.
- In general, do not execute any repair or kit replacement during this process that will take longer than **5 minutes.** If it will take longer than 5 minutes, it should be deferred until after this phase is complete.
- There are three inboxes for finished inventory sheets where they'll be deposited after a staffer is done inspecting and cleaning each kit:
  - Ready to Digitize: Sheets in this pile either have no issues with their physical contents or details on the inventory sheet, OR the only adjustments that need to be made are updating fields in the booking system for the item during digitization.
  - Repair/Purchase: The item will need a detailed repair (either in-house or shipped out), or it's unclear whether we have a backup component available to replace a broken or missing one. Sheets in this pile will be turned into tickets to replace missing components from kits or generate purchase requests for replacement parts.
  - Quick Fix: The kit's issues are easily corrected using existing inventory or repair skills but it may take longer than 5 minutes. (for example, it needs velcro ties for all cables or it needs a new connector resoldered).

Once "Quick Fix" items are complete, they can be moved to "Repair/Purchase" if further action is needed, or "Ready to Digitize" if all physical issues have been documented with a ticket or resolved already by a staffer. 

### Phase 2: Digitization
- Create Circulation Tickets in Tasks for any items in the "Repair/Purchase" list, copying the notes from the staffer who completed the inventory. Move these sheets to the "Ready to Digitize" pile.
- Try to keep collections and items in similar categories together, as they may have become jumbled during the inventory process.
- Update each item in BookIt appropriately. After all changes have been made to the digital entry, update the item's "last inventoried" date (in the Service History section) to the day it was inspected and initial on the page with a different color ink than the initial inspection to show it has been completely finished/had its problems logged for in Tasks for further action. 
- Archive the sheet but do not throw them away until all sheets have been processed and issues resolved, as they may need to be referenced. 

## Kit Pics and Quick Start Guides

### Kit Pic
Kit Pics are visual inventories included with circulating items. They help patrons and staff identify individual components within a kit as they complete the checkout receipt.

Kit pics should be included in kits that have:
- Small, similar looking parts (e.g. Ronin RS2 camera gimbal)
- Parts with specialized names that are not immediately identifiable to a layperson. (rule of thumb: if your mom couldn't identify it without help, it should have a kit pic)

Creating a kit pic:
- Make a folder in **[directory here]** for the Kit Pic InDesign file, component pictures, and finished PDF. Save a new InDesign file from the **[template]**.
- Find or take photos for each component and save them in the Teams file folder with the InDesign file. Component pictures on the kit pic should:
  - **Look like the components in the kit.** Many parts can be made by different manufacturers and have different finishes. Try to find a picture online that matches the item in the kit, or take your own photo of the item!
  - **Have the same name as the component list.** This is what prints on the receipt the patron completes during a checkout (and appears on the `Kit Contents` page of each item in the public BookIt listing). The caption under the picture of a component should match exactly with the name of the component on the list.
  - You may need to use Photoshop to remove the backgrounds of any component photos you take or find on the Internet.
- `Place` the photos in the appropriate content boxes and resize them to fit.
- Make sure the barcodes on each page are correct, especially if preparing new kit pics for multiple similar kits.
- Print the kit pic in color and double-sided on regular paper, making sure it's the correct quarter-page size.
- Cut the pages out and laminate them, and then put a grommet and washer on each page where indicated.
- Bind together with a zip-tie or ring (you can find them in the Circ Room).
- Put in the kit and update the Maintenance Log and mark the assigned Task as complete.

### Quick Start Guides
Quick Start Guides are short guides that help patrons use our equipment. Not all kits have quick start guides.

Guides should:
- Include step-by-step guides for common operations
- Include illustrations/diagrams for common features specific to the device in the kit
- Reinforce policies and processes from the authorization video and "show me" training with DMC staff (if applicable)
- Be concise and no longer than a few pages.
- Point users to other resources for reference and learning (e.g. DMC website, manufacturer manual, etc.)
- Fit within the item kit without folding - scaled down to quarter or half-sheet, and laminated/grommeted like kit pics.
- Use DMC fonts, colors, and include DMC contact information.
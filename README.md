# <u>WESTERN GOVERNOR UNIVERSITY </u>

TASK C.
- mainscreen.html, line 19: Changed header to 'Old Castle Technology'
- mainscreen.html, line 18: Added a background color of 'light'
- mainscreen.html, line 22: Changed 'Parts' to 'PC Chassis'
- mainscreen.html, line 54: Changed 'Products' to 'Accessories'
- mainscreen.html, line 14: Changed the title of the webpage

TASK D.
- about.html: Added the about page
- mainscreen.html, line 21: Added the about page button
- AboutController.java: Added the AboutController file

TASK E.
- Product.java, line 108: Added the setQuantity method
- BootStrapData.java, line 70-85 & 95-112: Added 5 parts/products with supporting methods

TASK F.
- mainscreen.html, line 86-89: Added a form for the 'Buy Now' button
- BuyProductController.java: Added the controller for the /buyProduct
- purchaseSuccess.html: Added the purchaseSuccess template
- purchaseError.html: Added the purchaseError template

TASK G.
- InhousePartForm.html, line 25-29: Added min/max input fields
- OutsourcedPartForm.html, line 25-29: Added min/max input fields
- Part.java, line 31-35: Added minInv and maxInv
- Part.java, line 45-51: Edited constructor to take minInv and maxInv
- BootStrapData.java, line 73-77: Added min/max values to parts
- BootStrapData.java, line 95-101: Edited addPart method to take minInv/maxInv
- Part.java, line 129: Checks if inventory is between min and max
- AddInhousePartController.java, line 43-46: Check if it's out of range
- AddOutsourcedPartController.java, line 44-47: Check if it's out of range
- application.properties, line 6: Changed name of database file to spring-boot-2

TASK H.
- AddInhousePartController.java, line 46-49: Display error for low inventory
- AddOutsourcedPartController.java, line 47-50: Display error for low inventory
- EnufPartsValidator.java, line 36-40: Display error messages when adding and updating parts if the inventory is greater than the maximum

REVISIONS
- BootStrapData.java, line 96: Changed Part to InhousePart object
- AddInhousePartController.java, line 45: Changed message to be more specific
- AddOutsourcedPartController.java, line 46: Changed message to be more specific
- Part.java, line 53-57: Commented out the extra constructor
- Part.java, line 32 & 35: Changed min/max values from private variables
- EnufPartsValidator.java, line 33-37: Took out my extra logic, used original file
- InhousePartForm.html, line 37-38: Added a link to go back to mainscreen
- productForm.html, 74-75: Added a link to go back to mainscreen
- about.html, line 20: Edited link to go back to mainscreen
- mainscreen.html, line 21: Edited link to go back to about
- InhousePartForm.html, lines 17, 20, 24, 27, 30: Added labels to fields
- OutsourcedPartForm.html, lines 18, 21, 24, 27, 30: Added labels to fields
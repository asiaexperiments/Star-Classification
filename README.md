# Star-Classification

## Our data mining project aims to classify objects in space, such as stars, planets, and other celestial bodies. It uses features like brightness, size, radiation, and shape to predict whether an object is a star and determine its type.

### Objective
1. To classify objects in space as stars or non-stars.
2. To further classify stars into specific types based on their features (e.g., brightness, radiation levels, size, etc.).
3. To explore and understand the criteria used for celestial classification in astronomy.

### DATA Content
The data consists of 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy or quasar.

1. obj_ID = Object Identifier, the unique value that identifies the object in the image catalog used by the CAS
2. alpha = Right Ascension angle (at J2000 epoch)
3. delta = Declination angle (at J2000 epoch)
4. u = Ultraviolet filter in the photometric system
5. g = Green filter in the photometric system
6. r = Red filter in the photometric system
7. i = Near Infrared filter in the photometric system
8. z = Infrared filter in the photometric system
9. run_ID = Run Number used to identify the specific scan
10. rereun_ID = Rerun Number to specify how the image was processed
11. cam_col = Camera column to identify the scanline within the run
12. field_ID = Field number to identify each field
13. spec_obj_ID = Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)
14. class = object class (galaxy, star or quasar object)
15. redshift = redshift value based on the increase in wavelength
16. plate = plate ID, identifies each plate in SDSS
17. MJD = Modified Julian Date, used to indicate when a given piece of SDSS data was taken
18. fiber_ID = fiber ID that identifies the fiber that pointed the light at the focal plane in each observation

Stellar Classification Dataset - SDSS17. Retrieved from https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17.

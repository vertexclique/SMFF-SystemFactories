Additional Documentation to get this project running

This package provides factories to create system models.


Depends on the following SMFF packages 
- SMFF-Core				(for Model definition) 
- SMFF-ModelExtensions	(only required for the JConstraintFactory) - This dependency actually is quite ugly
						 as it will cause a dependency to symta and jdom. However, I see no other way to make
						 model extensions XML- and Symta-Saveable without referencing the corresponding packages.
						 If you come up with a better solution feel free to change it.

Required Java Libraries
- none
 
Additional Requirements
- none  
# simplevisa
Simple to use interface for different measurment devices using pyvisa and ni-visa over GPIB, USB etc.
Install with:
* pip install simplevisa

## (Partially) Supported instruments
* HP856x Series Spectrum Analyzer 
	* Agilent 8562EC
	
* HP663xA Series System Power Supplies 
	* HP6632A
	* HP6622A
	
* Rohde & Schwarz SMTxx Series Signal Generators
	* SMT03
	* SMIQ03
	
* HP / Agilent Switch Module
	* HP3488 
	
* Rigol Multimeter (Compatible with Agilent and Fluke Protocol)
	* Rigol DM3068 (USB)
	
## Scripts
### HP662xA Test 
Runs trough CC and CV range while logging and ploting 			
Voltage and Current by the Rigol DM3068 Multimeter.

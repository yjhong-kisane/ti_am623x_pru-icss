Programmable Real-time Unit (PRU) Software Support Package
------------------------------------------------------------
============================================================
	AM62x EXAMPLES
============================================================

DESCRIPTION

	This directory provides basic "building block" examples for the AM62x
	PRU-SS cores. The concepts shown in these examples can be combined to
	create PRU-SS applications.


WHAT EXAMPLES ARE INCLUDED?

	EXAMPLE
	---------
	PRU_Halt
		Halt is the basic empty PRU project.
		The core gets initialized, and then does nothing.

	PRU_Direct_Connect0
	PRU_Direct_Connect1
		Direct_Connect examples demonstrate how to:
		 * Pass INTC configuration to Linux RemoteProc driver
		 * Pass interrupts and data between PRU cores

	PRU_MAC_Multiply_Accum
		MAC_Multiply_Accum example demonstrates how to:
		 * check Data RAM usage
		 * Use the multiply with accumulate (MAC) module. See TRM for
		   more information

	PRU_RPMsg_Echo_Interrupt0
	PRU_RPMsg_Echo_Interrupt1
		RPMsg examples demonstrate the RemoteProc RPMsg protocol to
		communicate between the ARM and the PRU. RPMsg is not the best
		inter-processor communication method for every design, but it is
		useful for initial debugging and demonstrations.




ADDITIONAL RESOURCES

	For more information about the PRU, visit:

	PRU-ICSS Wiki            - http://processors.wiki.ti.com/index.php/PRU-ICSS
	PRU-ICSS/PRU_ICSSG docs	 - http://software-dl.ti.com/processor-sdk-linux/esd/docs/latest/linux/Foundational_Components_PRU-ICSS_PRU_ICSSG.html
	Linux SDK Support	 - http://software-dl.ti.com/processor-sdk-linux/esd/docs/latest/linux/index.html
	PRU Training Slides      - http://www.ti.com/sitarabootcamp
	PRU Evaluation Hardware  - http://www.ti.com/tool/PRUCAPE
	AM62x TRM                - Link TBD
	Support                  - http://e2e.ti.com

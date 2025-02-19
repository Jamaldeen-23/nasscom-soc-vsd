# nasscom-soc-vsd
Repository for the workshop "Digital VLSI SoC Design and Planning"

Lab Day 1 : Inception of open-source EDA, OpenLANE and Sky130 PDK
The objective is to perform the synthesis of the 'picorv32a' design and calculate the resulting flop ratio.


  # Step 1: Change directory to the OpenLANE flow directory within the OpenLANE working directory
  $ cd Desktop/work/tools/openlane_working_dir/openlane

  # Step 2: Execute the aliased 'docker' command to access the bash
  $ docker

  # Step 3: Start OpenLANE in interactive mode
  %./flow.tcl -interactive

  # Step 4: Load the required packages
  %package require openlane 0.9

  # Step 5: Prepare the 'picorv32a' design for synthesis
  %prep -design picorv32a

  

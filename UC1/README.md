# Risk Assessment of an Autonomous Cargo Ship
This folder contains the inputs and outputs of a risk assessment process conducted against an autonomous cargo ship architecture using the FAA approach.

The autonomous ship architecture is modelled as a graph using the ORA software (http://www.casos.cs.cmu.edu/projects/ora/software.php). The different modelled graphs are made available in this repository as well.

# Input Tables
This folder includes the tables that are used for the risk assessment process. The tables are:
- CCST: Filled in Step 4 in the process, the Component Criticality Scores Table includes the impact estimation of components for each impact element (safety, financial, information, etc.)
- CDT: Filled in Step 1 in the process, the Component Description Table includes the list of components covered within the risk assessment scope in addition to their attributes.
- CMT: Filled in Step 3 in the process, the Component Mitigation Table includes the mapping between the mitigation methods and the components covered by each one.
- FMMT: Filled in Step 4 in the process, the Failure Mode Metric Table includes the mapping between the failure modes (ATT&CK and ATLAS Tactic and Impact Techniques) and the metrics used to measure their impact. For instance, the Exfiltration tactic can be estimated using IC (Information Criticality) metric.
- FMT: Filled in Step 3 in the process, the Failure Mitigation Tabe includes the mapping between the failure mechanisms (ATT&CK and ATLAS Techniques) and their relevant mitigations (ATT&CK and ATLAS Mitigations) as well as the mitigation estimated efficiency.
- TDT: Filled in Step 5 in the process, the Threat Description Table includes the list of all threats to be considered in the assessment (ATT&CK and ATLAS Techniques) in addition to their attributes.

# Ora Networks
This folder includes the graphs of the autonomous ship targeted by the assessment.
- Auto-Cargo-Control.xml: is a graph of the component utilized for the controlling functions.
- Auto-Cargo-Mnitor.xml: is a graph of the component utilized for the monitoring functions.
- Auto-Cargo.xml: is a graph of all the components in the network.

# Results
This folder includes the output of the assessment process in three documents:
- Excel sheet containing the results in an excel sheet with additional sheets with additional insights.
- JSON format containing the raw results.
- CSV format containing the raw results.

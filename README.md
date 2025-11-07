# ToolWindowAnalytics-Task
Download content it was made in jupyter lab online so i posted it here


# Tool Window Usage Analysis

Reconstructs open→close episodes from IDE logs and compares how long the tool window stays open when launched **manually** vs **automatically**. 
Covers two double-OPEN cases: either the previous episode is **force-closed** at the moment of the second OPEN, or the **second OPEN is ignored**. 
Includes a quick robustness check with the **winsorized mean (p1–p99)**, plus concise charts (counts, boxplot, ECDF) and a short summary with key numbers and a simple significance test.


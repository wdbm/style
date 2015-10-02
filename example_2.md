# main title

This is text.

# title

## subtitle

This is text. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## code

This is code:

```Bash
cd "${TTHBBLEPTONICDIR}"/..
selection_variables_comparison.py \
    --variables=jet_pt[0],jet_pt[1],jet_pt[2] \
    --selections=e_jets \
    --histogram1Legend="p2352" \
    --histogram2Legend="p2375" \
    --ROOTFile1=TTHbbLeptonic/share/output_example_p2352.root \
    --ROOTFile2=TTHbbLeptonic/share/output_example_p2375.root \
    --configuration="TTHbbLeptonic/share/configuration.md" \
    --normaliseToUnity \
    --verbose
```

## tables

### variables common to dilepton and lepton + jets run one analyses

|**variable**|**description**|
|---|---|
|Centrality_all|centrality calculated using all jets and leptons|
|Mbb_MindR|mass of ${bb}$ pair with minimum ${dR}$|
|dRbb_MaxPt|${dR}$ of ${bb}$ pair with maximum ${p_{T}}$|
|Mjj_MaxPt|mass of ${jj}$ pair with maximum ${p_{T}}$|

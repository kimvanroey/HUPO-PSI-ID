## HUPO-PSI-ID protein-centric JSON exchange format

***Description***: Exchange of the experimentally characterised protein regions for a given protein.

***Schema***: The draft schema for the protein-centric structural experiment JSON exchange format is [here](https://github.com/normandavey/HUPO-PSI-ID/blob/master/ELIXIR_biohackathon/miade_protein_centric.schema.json).

***Example***: An example of the draft schema for the protein-centric structural experiment JSON exchange format is [here](https://github.com/normandavey/HUPO-PSI-ID/blob/master/ELIXIR_biohackathon/miade_protein_centric.schema.example.json).

***Usage***:
Data keys for which no data is available should not be added to the JSON object

***Options***:

UniProt identifier - return data for a given protein
No options specificied - return data for all proteins in database

***Details***:

Single protein: return single json dictionary
Multiple protein: return array of json dictionaries

***Available endpoints***: 

BMRB: 

* BMRB protein entry: http://webapi.bmrb.wisc.edu/development/protein/uniprot/Q86T24?format=hupo-psi-id

* BMRB protein all entries: http://webapi.bmrb.wisc.edu/development/protein/uniprot?format=hupo-psi-id

DisProt: 

* DisProt protein entry: https://disprot.org/api/P04637?format=psi-id-json

* DisProt protein all entries: https://disprot.org/api/search?format=psi-id-json 

PCDDB: Under development [here]()

SASBDB: Under development [here]()

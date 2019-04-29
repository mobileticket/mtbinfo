SCHEMACHECK=	python3 ../scripts/schemacheck.py
SCHEMADIR=	.

check:
	$(SCHEMACHECK) $(SCHEMADIR)/mtbinfo.yaml

json: mtbinfo.json

mtbinfo.json: mtbinfo.yaml
	python3 ../scripts/schemacheck.py  --json mtbinfo.yaml  > mtbinfo.json

SCHEMACHECK=	python3 ../scripts/schemacheck.py
SCHEMADIR=	../schemata

check:
	for example in *.json; do $(SCHEMACHECK) --input $$example $(SCHEMADIR)/mtbinfo.yaml; done

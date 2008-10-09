EXTRA_DIST =				\
	sources.xml
api:
	$(GAPI_PARSER) sources.xml

get-source-code:
	bzr branch ../../wizbit-new wizbit
	cd wizbit && ./autogen.sh && make

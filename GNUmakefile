
ZIPFILE := numbas-upm-theme.zip
FILES   := $(shell find src -type f)

$(ZIPFILE): $(FILES)
	(cd src && zip -ur ../$@ $(^:src/%=%))

.PHONY: all clean
all: $(ZIPFILE) 
clean:
	$(RM) $(ZIPFILE)

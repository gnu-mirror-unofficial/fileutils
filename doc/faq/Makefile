
.PHONY : all
all: core-utils-faq.info core-utils-faq.html

core-utils-faq.html: core-utils-faq.texinfo
	makeinfo --no-split --html core-utils-faq.texinfo

core-utils-faq.info: core-utils-faq.texinfo
	makeinfo core-utils-faq.texinfo

.PHONY : clean
clean:
	rm -f core-utils-faq.info core-utils-faq.html


build:
	for rst in src/*.rst; do \
		rst2pdf $${rst} $${rst%rst}pdf; \
	done;

	pdfunite src/*pdf haskell-inro.1.functional-purity-in-haskell.pdf

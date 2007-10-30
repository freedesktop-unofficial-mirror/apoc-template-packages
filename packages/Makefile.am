pkgsdir=${datadir}/apoc/packages

dtddir=${pkgsdir}/dtd
dtd_DATA = dtd/policytemplate.dtd


install-data-local:
	test -z "${pkgsdir}" || mkdir -p "${pkgsdir}"
	cp -r Evolution1.4_pkg/ ${pkgsdir}
	cp -r Gnome2.6_pkg/ ${pkgsdir}
	cp -r Mozilla1.4_pkg/ ${pkgsdir}
	cp -r StarOffice8_pkg/ ${pkgsdir}

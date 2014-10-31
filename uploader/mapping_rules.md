title: Mapping rules
authors:
    then
    john.jones

These are rules for connecting filenames in the archive to URLs on the website.

The format is pairs of lines, the first in each pair being a regular expression to match, and the second is a replacement string.  The first regular expression that matches is used to generate the URL to relate the filename to.  If there is no match then related_to is left blank.

<h4> Examples </h4>
Files:

	./EC/11a
	./EC/14a
	./EC/15a
	./EC/17a
	./EC/19a
	./EC/20a

Rules:

	.*/(.*)
	/L-function/EllipticCurve/Q/$1

Result:

	/L-function/EllipticCurve/Q/11a
	/L-function/EllipticCurve/Q/14a
	/L-function/EllipticCurve/Q/15a
	/L-function/EllipticCurve/Q/17a
	/L-function/EllipticCurve/Q/19a
	/L-function/EllipticCurve/Q/20a

Rules:

	./EC/1
	/L-function/EllipticCurve/Q/1
	./EC/2
	/L-function/EllipticCurve/Q2/2

Result:

	/L-function/EllipticCurve/Q/11a
	/L-function/EllipticCurve/Q/14a
	/L-function/EllipticCurve/Q/15a
	/L-function/EllipticCurve/Q/17a
	/L-function/EllipticCurve/Q/19a
	/L-function/EllipticCurve/Q2/20a

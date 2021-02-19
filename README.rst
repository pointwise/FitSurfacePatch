FitSurfacePatch
==================
A Pointwise Glyph script which creates b-spline surfaces from a set of connected bounding curves
and is fit to a shell (faceted) database.

Usage
~~~~~
This script can only be run interactively.

Select one or more shell database surfaces and one or more sets of connected bounding curves. The script will invoke the surface fitter mode which will create as many surfaces as possible, and fit them using the shell database entities as a point cloud. It is recommended to project or draw the bounding curves onto the shell database entities of interest. The script can be modified to run the surface fitting routine for as many iterations as desired.

.. image:: https://raw.github.com/pointwise/FitSurfacePatch/master/FitSurfacePatchExample.png

Disclaimer
~~~~~~~~~~
Scripts are freely provided. They are not supported products of Pointwise, Inc. Some scripts have been written and 
contributed by third parties outside of Pointwise's control.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, POINTWISE DISCLAIMS ALL WARRANTIES, EITHER EXPRESS OR IMPLIED, 
INCLUDING, BUT NOT LIMITED TO, IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, WITH REGARD 
TO THESE SCRIPTS. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL POINTWISE BE LIABLE TO ANY PARTY 
FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR 
LOSS OF BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR INABILITY TO USE THESE SCRIPTS 
EVEN IF POINTWISE HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES AND REGARDLESS OF THE FAULT OR NEGLIGENCE OF 
POINTWISE.

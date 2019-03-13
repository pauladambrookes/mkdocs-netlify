## Add Spectra to an MS Library

You can add spectra from a chromatogram to a new or existing custom MS library(an MS library created in Chromeleon).

###To add spectra to a custom MS library

1.  Display a mass spectral plot in the Data Processing or Report
    Designer view.

2.  Click the plot to make it the active plot.

3.  On the Studio ribbon, under <span class="hcp1">Spectral Plot
    Tools</span>, click the <span class="hcp1">Library</span> tab.

4.  In the <span class="hcp1">Manage</span> group, select an existing MS
    library or create a new library (see [Create a New MS Library] ). In
    the following example, spectra will be added to a library named
    <span class="hcp1">Library 1</span>, which currently does not
    contain any spectra.

    <img src="../SpectralLibrary/AddSpectrumFirst.png" class="hcp2" />

5.  To add the spectrum currently displayed in the mass spectral plot,
    click <span class="hcp1">Add Spectrum</span>.

!!! note
	If more than one spectrum is currently displayed, and if the plots are overlaid, the spectrum the mouse pointer is resting on is added. If the plots are stacked, the spectrum identified by the title on the top border of the plot is added.

To add the spectra of all peaks identified with a peak name in the
current chromatogram, click the down arrow and click <span
class="hcp1">Add All Spectra</span>. For example, if there are currently
16 named peaks in the chromatogram, 16 spectra are added to the library.
The apex spectrum for each named peak is added to the library.

<img src="../SpectralLibrary/AddAllSpectrum.png" class="hcp2" width="164" height="96" />

To add the

  [Create a New MS Library]: MSLibraries_Create_New.htm
  
##Create a New MS Library

You can create a new MS library in the
<a href="javascript:void(0);" id="a3" class="BSSCPopup">Chromatography Studio</a>.
After creating the library, you can add spectra from a chromatogram to
the library.

###To create a new MS library

1.  Display a mass spectral plot in the Data Processing or Report
    Designer view.

2.  Click the plot to make it the active plot.

3.  On the Studio ribbon, under <span class="hcp1">Spectral Plot
    Tools</span>, click the <span class="hcp1">Library</span> tab.

4.  In the <span class="hcp1">Manage</span> group, click the down arrow
    and select <span class="hcp1">Create new library</span>.

    <img src="../SpectralLibrary/CreateNewLibrary.png" width="233" height="96" />

    (In this example, the sequence already contains a library named
    PAH16.)

5.  Type the library name and click <span class="hcp1">OK</span>. A new
    empty MS library is created.

###Related Topics

[Add Spectra to an MS Library]: MSLibraries_Add_Spectra

##Export a Spectrum to NIST MS Search

If the NIST MS Search program is installed on your computer, you can
export a spectrum from Chromeleon to the NIST program to perform a
library search.

### To export a spectrum to NIST


1.  In the Chromatography Studio, display the spectrum of interest on
    the mass spectral plot (see [Select UV-Vis or Mass Spectra]).

2.  Right-click anywhere on the plot and click <span class="hcp1">Export
    to NIST</span>.

When you select the Export to NIST command,
Chromeleon creates a temporary data file that contains spectrum
information in a text format that can be used in a NIST library search.
The NIST MS Search program opens using this temporary file.

### Related Topics

[Ad Hoc Library Search]

[View Mass Spectral Plots]

[Open MS Raw Data in an External Application]

  [Select UV-Vis or Mass Spectra]: ../SpectralView/SpectralView_Select_Spectra.htm
  [Ad Hoc Library Search]: ../MSLibrary_CSH/MSLibrary_Ad-Hoc_Library_Search.htm
  [View Mass Spectral Plots]: ../SpectralView/SpectralView_ViewPlots_MS.htm
  [Open MS Raw Data in an External Application]: ../Console/Console_Data_RawFile_OpenWith.htm
  
##Find Spectra in an MS Library

You can search MS libraries for mass spectra that are similar to a
spectrum displayed on a mass spectral plot. This is referred to as an
"ad hoc" search.

!!! note
	You can also export a spectrum from Chromeleon to the NIST MS Search program, and then use the NIST program to perform a library search (see <a href="MSLibraries_Export_To_NIST.htm">Export a Spectrum to NIST MS Search</a>).

To find spectra in an MS library
--------------------------------

1.  Use one of the following methods to open an Ad Hoc Library Search
    window:

2.  Display the mass spectrum of interest in the Data Processing view
    (see [View Mass Spectral Plots]) and click the mass spectral plot to
    make it the active plot. On the Studio ribbon, under <span
    class="hcp1">Spectral Plot Tools</span>, click the <span
    class="hcp1">Library</span> tab, and then click
    <img src="../SpectralLibrary/FindInLibrary.png" width="77" height="69" />.

    –OR–

3.  Display the mass spectrum of interest in the Data Processing view.
    Right-click the mass spectral plot and select <span
    class="hcp1">Find in Library</span>.

    –OR–

4.  On the chromatogram plot, right-click the curve at a retention time
    of interest and select <span class="hcp1">Find Spectrum in
    Library</span>. A retention time spectrum is created where you
    clicked and the search is performed on the spectrum.

After you click <span class="hcp1">Find in Library</span>, the Ad Hoc
Library Search window appears and displays a list of the possible
matching spectra (hits). The first spectrum listed has the highest match
and the best similarity to the original spectrum.

N

  [View Mass Spectral Plots]: ../SpectralView/SpectralView_ViewPlots_MS.htm
  
##Add MS Libraries to the Search List

Any NIST 08, NIST 11, or NIST 14 format library can be included in an MS
library search, including:

-   Libraries copied from somewhere else

-   Libraries installed with the NIST MS Search program

-   Libraries created in Chromeleon (custom MS libraries)

The list in the following example contains one library of each type, in
the order described above.

<img src="MSLibrarySearchList.png" width="705" height="203" />

###To manually add a NIST library

1.  Go to either the MS Library Screening page of the Processing Method
    Editor or the Ad Hoc Library Search window.

	-   If you want to use the library for data processing of injections in
    a sequence, go to the MS Library Screening page.

	-   If you want to use the library to search for spectrum that you
    select individually from peaks on a chromatogram plot, go to the Ad
    Hoc Library Search window.

2.  	Under <span class="hcp1">MS libraries to be searched in</span>,
    click <span class="hcp1">Add</span> and browse to the folder that
    contains the NIST library. The NIST library can be located on the
    local PC or on a network drive. Select the library folder and click
    <span class="hcp1">OK</span>.

!!! tip
	To include a library on the MS Library Screening page and in an Ad Hoc Library Search window, add it separately to each.

###Related Topics

[Ad Hoc Library Search]


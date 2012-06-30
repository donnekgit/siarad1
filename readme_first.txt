Readme
=====

This directory contains a Git version control repository for the Siarad Corpus, 2009, from the ESRC Centre for Research on Bilingualism in Theory and Practice, Bangor University, Wales (http://bilingualism.bangor.ac.uk).

The entire corpus history is included in the .git folder, and can be accessed using a Git client (http://git-scm.com).

Note that this directory is NOT the published version, which is available from another folder - at time of writing:
U:\College of Arts & Humanities\School of Linguistics & English Language\AHRC-codeswitching\data\Siarad

The beta files in this directory use the same marking style as the Miami and Patagonia corpora (2012), and would therefore be the basis for any revised edition of the Siarad corpus.

The alpha folder contains the published transcriptions (using the old-style marking) as first committed to version control.

The beta folder contains the files after conversion to the new precode marking.  Any future correction of typos, global fixes to standardise spelling should be done on the beta files.

The autoglossed folder contains the files with a gloss added by the Bangor Autoglosser (http://bangortalk.org.uk/autoglosser.php), with typeset versions in the pdf subfolder.

The audiofiles folder contains the recordings (in wav and mp3 format) which form the basis of the transcriptions.  Personal references have been beeped out, and Input from third parties who were unable to give their consent (marked www in the transcriptions) has been silenced.  Note that if the third party was talking in the same timeframe as one of the main speakers, the main speaker's words may also be partially silenced.  

The beeping was done manually using Audacity (http://audacity.sourceforge.net).  The silencing was automated using SoX (http://sox.sourceforge.net), and a script (anonymise_audio.php) in the Bangor Autoglosser.

The original unsilenced versions are in the unsilenced subfolder.

The corpus files (recordings and transcriptions) are copyright the ESRC Centre, 2012, and are released under the GPLv3 or later (http://www.gnu.org/licenses/gpl.html).

Linguistic or methodological queries should be addressed to Margaret Deuchar (m.deuchar@bangor.ac.uk).
Technical queries should be addressed to Kevin Donnelly (kevin@dotmon.com).

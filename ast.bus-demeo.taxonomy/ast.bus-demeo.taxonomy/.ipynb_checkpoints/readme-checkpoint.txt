Description of the BUS-DEMEO ASTEROID TAXONOMY bundle V1.0
==========================================================

Bundle Generation Date: 2020-06-12
Peer Review: 2009 Asteroid Review, 2009-06-03                                 
Discipline node: Small Bodies Node


Content description based on the data set catalog file description for the PDS3 version, EAR-A-VARGBDET-5-BUSDEMEOTAX-V1.0
==========================================================================================================================

Note: for PDS3 data sets migrated to PDS4, the following text is taken
verbatim from the data set description and confidence level note of the
PDS3 data set catalog file. In these cases, some details may not be correct
as a description of the PDS4 bundle.
                                                           
    The Bus-DeMeo asteroid taxonomy classification system, described in DeMeo 
    et al. (2009), is based on reflectance spectrum characteristics for 371   
    asteroids measured over the wavelength 0.45 to 2.45 microns.  This system 
    of 24 classes is constructed using principal component analysis, following
    most closely the visible wavelength taxonomy of Bus (1999), which itself  
    builds upon the system of Tholen (1984).  Nearly all of the Bus taxonomy  
    classes are preserved, with one new class (Sv) defined.                   
                                                                              
    Note that a 'w' following the taxonomic type indicates that the spectrum  
    has a slope greater than 0.25.  A ':' following the taxonomic type        
    indicates a questionable classification because of low quality or         
    questionable data.  Spectra with a ':' are not included in the mean       
    spectra.                                                                  
                                                                              
    This data set includes a table of classifications in the DeMeo-Bus system 
    for the 371 asteroids upon which the system is based.  It also includes   
    mean spectra for each of the classes, and the principal component scores. 
                                                                              
    Files included in the data directory:                                     
                                                                              
    demeotax.tab - Bus-DeMeo classifications for 371 asteroids.               
    meanspectra.tab - Mean spectra for each of the 24 classes.                
    demeorefs.tab - Full references for the published papers with the spectral
    observations used for the classifications, cited in demeotax.tab.         
    pcscores.tab - Principal component scores for the 371 asteroids.          
                                                                              
    Ancillary documents included in the documents directory:                  
                                                                              
    classdesc.asc - For each of the 24 classes, this document gives the column
    for that class in the meanspectra.tab file, a short physical description  
    of the spectrum, and the number of asteroids included in the class.       
    taxocard.pdf - Thumbnail spectra for each of the 24 classes, arranged on a
    single page for easy reference and comparison.                            
                                                                              
    References:                                                               
                                                                              
    Bus, S. J., Compositional structure in the asteroid belt: Results of a    
    spectroscopic survey. PhD thesis, Massachusetts Institute of Technology,  
    1999.                                                                     
                                                                              
    DeMeo, F., R.P. Binzel, S.M. Slivan, and S.J. Bus, An extension of the Bus
    asteroid taxonomy into the Near-Infrared, Icarus 202 160-180, 2009.       
                                                                              
    Tholen, D.J., Asteroid Taxonomy from Cluster Analysis of Photometry, Ph.D.
    dissertation, University of Arizona, 1984.


Known issues or problems with the data
======================================

    All classifications are consistent with the output from the online webtool
    at http://smass.mit.edu/busdemeoclass.html. Classifications that are      
    uncertain due to the quality of the spectral data are denoted by a colon  
    following the class designation.

PDS3 Source
===========

Version 1.0 of this bundle was migrated from version 1.0 of the PDS3 data set EAR-A-VARGBDET-5-BUSDEMEOTAX-V1.0.

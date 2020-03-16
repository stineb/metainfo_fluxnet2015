# metainfo_fluxnet2015

## Description

This repository contains reproducible code for collecting meta data for FLUXNET 2014 Tier 1 sites.

This is implemented in RMarkdown file:

- `prepare_metainfo_fluxnet2015.Rmd`

.. and creates a table with meta info for all sites CSV in 

- `output/siteinfo_fluxnet2015.csv`

## Citation 

Please cite original meta data providers.

- For Koeppen-Geiger climate classification of sites, and complementary site elevation data where missing in original FLUXNET 2015 dataset:

Falge, E., M. Aubinet, P.S. Bakwin, D. Baldocchi, P. Berbigier, C. Bernhofer, T.A. Black, R. Ceulemans, K.J. Davis, A.J. Dolman, A. Goldstein, M.L. Goulden, A. Granier, D.Y. Hollinger, P.G. Jarvis, N. Jensen, K. Pilegaard, G. Katul, P. Kyaw Tha Paw, B.E. Law, A. Lindroth, D. Loustau, Y. Mahli, R. Monson, P. Moncrieff, E. Moors, J.W. Munger, T. Meyers, W. Oechel, E.-D. Schulze, H. Thorgeirsson, J. Tenhunen, R. Valentini, S.B. Verma, T. Vesala, and S.C. Wofsy. 2017. FLUXNET Research Network Site Characteristics, Investigators, and Bibliography, 2016. ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/1530

- For complementary Koeppen-Geiger classification, where data is missing in Falge et al.:

Beck et al. (2018) *Scientific Data*, DOI: 10.1038/sdata.2018.214

- For complementary site elevation data where missing in original FLUXNET 2015 dataset and in Falge et al.:

Weedon, G. P., Balsamo, G., Bellouin, N., Gomes, S., Best, M. J., and Viterbo, P.: The WFDEI meteorological forcing data set: WATCH
Forcing Data methodology applied to ERA-Interim reanalysis data, Water Resour. Res., 50, 7505–7514, 2014.

- For water holding capacity (see Appendix D):

Stocker, B. D., Wang, H., Smith, N. G., Harrison, S. P., Keenan, T. F., Sandoval, D., Davis, T., and Prentice, I. C.: P-model v1.0: An optimality-based light use efficiency model for simulating ecosystem gross primary production, Geosci. Model Dev. Discuss., https://doi.org/10.5194/gmd-2019-200, in review, 2019.
# dataCleaning
Data cleaning is one of first task when working with data. data cleaning invloves lots of works like droping null values, outliers, editing string values and etc. 
is some cases we drop columns that have a most null values. somtimes they are filled with mean or median or top on data. 
packages like seaborn helps in creating heat map that gives us a insight view of data. pandas have plotting modules like histograms or boxplot that could be used in detecting outliers. 
when working with string values, there are some strings that have typo. for example 'Apple'=> 'Aple' or 'Newyork' => 'Newyurk' . we can handle this with edit distance alogrithms. it's ready in nltk.metrics module.
also in working with address atributes, we can convert symbols like 'street' or 'avenue' to 'st' and 'av'.

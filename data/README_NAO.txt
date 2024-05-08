NAO data are retrieved from https://crudata.uea.ac.uk/cru/data/nao/index.htm

As explained in the website the format of the file is as follows

for year = 1821 to endyear
format(i5,12f7.2,f8.2) year, 12 * monthly value, annual value
Missing values represented by -99.99

I add the first line to the file nao_3p.dat so that I can call each column easily.

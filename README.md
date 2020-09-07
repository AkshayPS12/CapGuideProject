# CapGuideProject

### Overview
The idea was to convert the PDF into a CSV file for further operations.
  
So I first used an open source library PDFminer but it had problems in recognising GOPENS etc as individual entities.

Then I used online PDF to CSV converter [ZAMZAR](https://www.zamzar.com/)
 
Then usual data cleaning using Pandas DataFrame attributes(Explained in code)

After fetching the row indexes for the given Home University query, I searched the corresponding branch query.

Getting the lists of College names and GOPENS/GOPENH corresponding to above data I constructed a DataFrame using the two lists.

Then I sorted the DataFrame using the cutoff rank as the key column to get the desired result.

### Second Task
For the Bonus Task along with GOPENS, I took the other queries as well(GSCS GSTS etc) and made a custom DataFrame and sorted it with multiple columns.

#### References available on request.

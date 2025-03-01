This file reads an excel file where the Portfolio Manager marks stocks in different colours. Each colour signifies a trade instruction.

The code picks the stocks that have to be traded based on the colours and runs a few checks to prevent human error.

Filtering is done to avoid blacklisted stocks etc.

Latest prices are pulled using the Refinitiv API.

Oreder files are formatted based on the order execution platform's format.

Apart from order files, the code also prepares a "Short Request" file which gets sent to Morgan Stanley through at FTP.

The "Short Request" file is created so that MS can give us real time information about the cost of borrowing and the number of shares availability of borrowing for a particular list of stocks.

The input file has not been attached due to confidentiality reasons.

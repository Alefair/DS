
# Research of data on the Russian film distribution

## Links
1

## Description
The customer of this study is the Ministry of Culture of the Russian Federation.
It is necessary to study the Russian film distribution market and identify current trends.

Special attention is paid to films that have received state support.


## Libraries
- [x] **matplotlib**

- [x] **pandas**
- [x] **datetime.datetime**
- [x] **bs4.BeautifulSoup**

- [x] **IPython.display.Markdown**
- [x] **matplotlib.pyplot**

- [x] **numpy**

- [x] **os**
- [x] **os.listdir**
- [x] **os.isfile, os.join, os.isdir**

## Сommon Сonclusion
**What have we learned about?**

- There are omissions and errors in the provided data, they should be reported to colleagues.

- Combined the data with the rental data to see the whole picture

- Looked at the data structure and looked at the data of each column where there are gaps.

- Converted int64 -> int32, float64 -> float32, and from object to datatime

- Corrected explicit and implicit duplicates and compared the data with the Kinopoisk website and with the website of the Ministry of Culture of the Russian Federation - the register of rental certificates

- Studied the categories and corrected their names, Studied the influence of categories on rental, combined the genre categories into a general category

- Checked the columns of the volume of refundable and non-refundable funds, and also studied the budget of films and fees in rubles

- Added a column with the year of release, which was obtained from the release date

- Added a column of the main director of the film

- Studied the most expensive film at the box office and the cheapest in fees

- Watched the share of state support in each film

- Found out that very few films were released in 2011, and the peak came in 2019

- Noticed that the highest box office receipts were in 2017, but we remember that then the film "Three Seconds" was released - the biggest box office film in the entire history of domestic film distribution

- And they also found out that the largest amount of public funds was provided for the film with famous actors Jackie Chan and Arnold Schwarzenegger 'Journey to China: The Mystery of Iron Mask', state support amounted to as much as 180,000 rubles of refundable funds

- And as a result, we found out that the most ideal film **is a feature film in the drama genre for people over 16 years old!**
<br><br>
**I suggest paying attention to the Drama genre with an age limit of +12. And use the state budget no more than 20%. This will be the golden mean :-)
For comparison, I suggested paying attention to the films "Three Seconds", "SON OF A RICH", "Posledniy Bogatier"**

I would like to end with a quote that we found out during the last study - **A high rating does not mean that the film paid off, yes, it may have failed at the box office, but it left its mark on history!**

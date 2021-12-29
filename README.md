# Chonkers gonna chonk
#### Video Demo:  <URL HERE>
#### Description:
Chonker is a colloquial term for a fat but photogenic cat. I have made a website that allows the user to assess the thickness of the cats in the photos according to a six-point scale. It is a form of fun and a reference to internet memes. That being said, I do not support fattening animals on purpose, by malnutrition or negligence.

The application was written in Python using Flask framework. The files have been placed in folders according to the MVC design pattern. I also prepared a responsive layout using HTML, CSS and Grid. 
  
Directory /templates contains files used to create final HTML. Directory /static contains directory /UI with elements of User Interface like logo of website and chart which is a visual aid to assess fatness of cats. In /static you will also find CSS style sheet (styles.css), jquery file and directory /cats which contains different cats images. All python code for web server is in the file app.py. The database (chonkers.db) was created using sqlite3. It consists of two tables. In the first one (Users), the login details are saved. The second table (Ratings) is used to create ratings - how many photos the user has rated. 

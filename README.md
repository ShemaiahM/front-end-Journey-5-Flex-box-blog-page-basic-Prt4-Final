# front-end-Journey-5-Flex-box-blog-page-basic-Prt4-Final
front-end-Journey-5-Flex-box-blog-page-basic/ webpage basic blog practice(4th one) finally got the web layout for a very basic blog 

<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/7ff5f01c-3c23-4f16-acd7-ae37910ce8ba" />

### Basic Blog
- The last week I have rewatching and learning from the videos from My Software development course(front end ), I am watching the Html & Css and relearing wjat  ive learnt.
- In this exercise i have demonstrated the use of Html(hyper text markup language) syntax and CSS (Cascading Style Sheet) syntax and semantics.
  #### here are the components of the "code" written
  ##### Html
  -*** ``` <nav class="navbar">
        <ul>
          <li><a href="">home</a></li>
          <li><a href="">about</a></li>
          <li><a href="">projects</a></li>
          <li><a href="">contact</a></li>
        </ul>
        <div class="btns">
          <button>sign up</button>
          <button>login</button>
        </div>
      </nav>`
  - -`  <footer class="footer">
    <ul>
      <li><a href="">Made with love</a></li>
      <li><a href="">S M</a></li>
      <li><a href="">contact me here</a></li>
    </ul>
    <p>&#169 all right reserved</p>
  </footer>```***

  
##### Css
-*** `/* nav bar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border: 2px solid black;
  padding: 20px;
  background-color: aquamarine;
  font-size: 20px;
  width: 100%;
  & ul {
    display: flex;
    gap: 10px;
  }
  & li {
    list-style: none;
  }
  & a {
    text-decoration: none;
    color: black;
    font-weight: bold;
    font-family:
      "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  }
}`***
-***`/* card container */
.card-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  flex-wrap: wrap;
  padding: 40px;` ***

  
***`/* cards */`
- `.card {
  margin: 20px;
  border: 1px solid black;
  border-radius: 20px;
  overflow: hidden;
  display: flex;
  justify-content: center;
  text-align: center;
  flex-direction: column;
  width: 300px;
  box-shadow: 1px 2px 0px black;`***


-- for the cards i used a utilty class instead of making every one.
  -- I have also used short form and more precise and clean code nesting in the css styles instead of individually separating the ul, li and a tags.
  -- If you look at my code for CSS yo can see what i have documented.

#### Conclusion
- Last week was the first proper full week of study and rewatching and learning basic html and css. I have still alot to learn even with flex box and page sizing and getting comfortable with making my own. I still have to go through the basic and traininig again.
- LastlyThank you Mido And Lead fo rthe resources. 

# Williams

A landing page of a SAAS company (Williams Company), a company that hosts an application and makes it available to customers over the internet. This landing page was the designed by (https://www.behance.net/jonathanadah01).

# Screenshot
![williams](https://user-images.githubusercontent.com/74037448/188327734-17468b7c-1607-48a2-9da6-62fadf854281.JPG)
![williams3](https://user-images.githubusercontent.com/74037448/191754032-60080ea9-d8d7-455e-9d98-f4efd865cb66.JPG)
![williams4](https://user-images.githubusercontent.com/74037448/191754035-ca58acf6-8d56-45ee-a270-51f82521e39d.JPG)
![williams5](https://user-images.githubusercontent.com/74037448/191754039-a9c9909f-3154-40f2-9493-bfd334299a90.JPG)
![williams6](https://user-images.githubusercontent.com/74037448/191754043-db9a468b-70c6-494b-b563-05546d5e0bb4.JPG)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- jQuery (Animation On Scroll for the animation).
- Bulma Css
- javaScript

## What I Learnt

- I was able to practice React Routers and how to navigate through pages of a site without the page refreshing, with the use of the "link" tag instead of the regular "a" tag.

```js
    <Router>
      <>
        <Navbar />
        <Switch>
          <Route exact path="/">
            <Body />
          </Route>
          <Route exact path="/pricing">
            <Pricing />
          </Route>
          <Route exact path="/signup">
            <Signup />
          </Route>
          <Route exact path="/contact">
            <Contact />
          </Route>
          <Footer />
        </Switch>
      </>
    </Router>
```


- I learnt to use Helmet to give each page a unique title instead of relying on the "title" tag in "index.html". You can see how below:

```js
      <Helmet>
        <meta charSet="utf-8" />
        <title>Contact Us | Williams Limited</title>
        <link rel="canonical" href="http://mysite.com/example" />
        <meta
          name="description"
          content="Contact Us Page For William SASS website"
        />
      </Helmet>
```

- I was also able to appreciate the use of % in pure css because it makes responsiveness easier to manupulate using media query.



## Author

- Twitter - [@_henryi](https://www.twitter.com/_henryi)
- LinkedIn - [Henry Agu](https://www.linkedin.com/in/agu-henry-871a981b0)
- Instagram - [@i_am_henry69](https://instagram.com/i_am_henry69?igshid=YmMyMTA2M2Y=)





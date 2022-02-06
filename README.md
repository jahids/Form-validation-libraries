<h1 align="center">
  <a href='https://jahids.github.io/Form-validation-livery/src/template.html'>Validator</a> - Lightweight & Easy simple  HTML form <em>Validator</em>
</h1>

The Validator is cross-browser and will give you the power to use future-proof input types such as:<br>
`first-name`, `last-name`, `email`, `phone` `url` and `https`.

# [Demo Live site](https://jahids.github.io/Form-validation-livery/src/template.html)

# how to use form validation

    // usage this Cdn:  <script src="https://cdn.jsdelivr.net/gh/jahids/Form-validation-livery/build/main.bundle.js"></script>

    // usage config code :  new testLibrary.default(document.getElementById('form'), {
      'first-name': { minLength: 2, nonNumeric: true },
      'last-name': { minLength: 3, nonNumeric: true },
      'my-email': { minLength: 5 },
      'phone': { minLength: 11, maxLength: 12 },
      'password': { hasUpperCase: true, hasLowerCase: true },
      'url': { hasHttps: true }
    })
    
    // You can show eror message you can use this html code
       <small id="first-name"  class="small"> </small>


### Why should you use this?

* every  browser support validation
* Flexible error messaging system
* Light-weight this livery
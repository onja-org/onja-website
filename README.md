# Onja website

## Source files

[Figma Design](https://www.figma.com/file/WukFhRHXNARUlN1sktJ6T1/Onja-Website?node-id=0%3A1)

## Development

### Workflow

`main` is the primary branch.

We'll be working in feature branches.

Create a new branch called: `feature/masthead`.

Those feature branches can only be merged via a pull-request once approval has been met. All feature branches will spawn off our Github Issues.

You can keep track of our progress in the Project screen.

## The way we did this contact form

- We create an html document(share.html with its css file named share.css)
- We use a section as a container to store the code
- The form has /contact-form action and all the user inputs are inserted inside of a few fieldset elements and we use border transparent in order to hide them.

### Testing

We use `testing` as our test branch. Merge your feature branches into testing to make sure your code works well with other's code.

### Naming

We're using [BEM](http://getbem.com/) as our class naming methodology.

Use the block class of each component as the file name for the CSS and pattern HTML file.

Images need a filename that describes what the image is portraying.

### Supported browsers

We're using relatively new CSS properties and selectors, so we're pegging our browser support at:

- Microsoft Edge (> v18)
- Chrome (latest)
- Firefox (latest)
- Opera (latest)

All testing will be done in:

- Edge (> v18)
- Chrome (latest)
- Firefox (latest)


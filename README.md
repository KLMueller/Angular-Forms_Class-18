# Class 18 - Forms

___write your experience of the different approaches.___
I found the approaches to be very similar. The template-driven approach does seem to be quicker in some areas with less code to be written, but the Reactive-driven form was still managable to the point that I could see myself using it again. The Reactive portion took me less time to complete but that's because I had learned so much through trial and error with the template section. I liked the learning approach of doing the two side-by-side, both within the assignment tasks and visually on the server.

 ____Write about what you find easy and what is challenging about each._____
I was struggling in the template section with getting interpolation to work correctly, so I took Max's approach of using the View Child and creating an array of object items in the TS file and that seemed to resolve the interpolation problem. With the Reactive section, I got hung up on using "valid" instead of "invalid" with the Validators but it was an error that was quickly found and resolved.

__Define the "Template-Driven-Approach" and the "Reactive-Driven-Approach".___
___Explain their differences and what each excel at doing._______

The Template-Driven forms are model-driven by directives in the template. It is used with simpler forms. With this approach, Angular infers the Form Object from the DOM.

The Reactive-Driven-Approach is model-driven and handles input that changes over time and that can be accessed synchronously. This approach is used with more complex forms and gives the programmer more control over how the form performs.  With this approach, the form is created programatically and synchronized with the DOM. It is easier to test large projects than template-driven because the data is consistent and predicatble.


## How to Start

1. On this page, find the green button that says "Code". Click it and download the ZIP file.
2. Unzip the folder and open in VSCode
3. Open a terminal at this folder and run `npm install` to download the node_modules dependencies.
4. Code!

---

## Steps

1. Download staring code for [class 10 Angular Example](https://github.com/WilderDev/Class-10-Angular-Forms-Example)
2. In the _app.component.html_ file, create a container div with a row inside that renders both of our components side-by-side.
3. Inside the "BookFormTemplateComponent": Create a template-driven form that, when submitted, displays all the relevant data below the form.
   - Title, Author, and Genre should all be required inputs that display an error message with a red border when touched and invalid.
   - Set 'mystery' to be the default value on the genre select box.
   - Use two-way-binding to display the name of the book after the word "Submit" on the submit button.
   - Display the title, author, and genre below the form when a user clicks "Submit". (Also, reset the form.)
4. Inside the "BookFormReactiveComponent": Create a reactive-driven form that, when submitted, displays all the relevant data below the form.
   - Title, Author, and Genre should all be required inputs that display an error message with a red border when touched and invalid.
   - Set 'mystery' to be the default value on the genre select box.
   - Display the title, author, and genre below the form when a user clicks "Submit". (Also, reset the form.)
5. (see above for response) Publish to Github. Inside the README.md file, write your experience of the different approaches.
   - Define the "Template-Driven-Approach" and the "Reactive-Driven-Approach".
   - Explain their differences and what each excel at doing.
   - Write about what you find easy and what is challenging about each.

---

## Viewing the Final Product

1. On this page in github, on the same line as the "code" button but on the left side... you should see a dropdown with the text "Starting-Code".
2. Click the dropdown and select "Final-Project".
3. You should now be able to view the files of the finished project.

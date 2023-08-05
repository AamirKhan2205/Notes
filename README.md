# Notes
REACT

Prerequisites :- NodeJs should be installed.
                        npm and npx are required.

npm :- npm is used for downloading required packages.
npx :- npx is required for executon of preinstalled packages,

Why react??
React basically allows developers to utilize individual parts of their application on both the client-side and the server-side, 
which ultimately boosts the speed of the development process. In simple terms, 
different developers can write individual parts and all changes made won't cause the logic of the application.

Steps to start a react app?
install all the prerequisites.
open the terminal on vs code.
type npx create-react-app <app-name>.
the react app will show up on screen as soon as all the requirements are been installed.

The HTML and JavaScript code is mixed up and is written in the index.js file which is located in the src folder,
and when you enter this folder you will observe that their is written import react written on the very top,
this is be now this package is very important as it brings in all the react stuff along with it for our development,and the second is react dom which is related to virtual dom,vritual dom is basically a property of react itself.

The language that is going to be used here is JSX which stands for javaScript Extension and is a mixture of javascript and HTML,following is the syntax to write it :-> ReactDom.render( 
                                                                     <React,strictMode/>                          
                                                                       <App/>                                                     
                                                                        <React,strictMode/>                           {'root' is the one allowing HTML on the
                                                                                                                                       other page to recognise the JSX code                                                                              
                                                                         document.getIdEleentById('root')          in this src folder.}
                                                                         );  

now we know that a website is basically a combination of several components , similiarily, <App/> here is a componenet within the src folder which holds all the JSx for the app we are goinf to make. 

you cannot directly copy paste a html code in jsx from bootstrap you willhae to convert the code into jsx first. 
whenever you create a new component you will have to import React their first by writing a shortcut 'imr'.
in order to a particular value of an attribute of an object and place it on the HTML we use 'props',props provide with a read only data,
i.e it cannot be changed and the syntax is {props} like this, whatever functions that is taking the whole object as an argument within,
itself you will hae to pass props within the parantheses of that function and then that particular prop becomes the object itself,and now you can
access the attributes by writing {props.<attributeName>} and set it on the veiw page.

so as we know that any property or attribute within your prop cannot be changed so what if we want to update a certain property,Example you want a certain change to occur in your specific attribute on clicking on a button what you can do is use a 'state' state have two properties 'setState' and 'useState'
we can use either of it for our benefits state particularly means the data you want to manipulate here.

Basically,'state' property works in such a way that it compares your virtual DOM with your real DOM and the notes the difference and reflects the one
we set to be shown on our HTML view page using 'setState()',you will have to keep that in mind that the change would not show up on your HTML until you use 'setState'.

whenever we want to create a state in a functional component we have to use a 'Hook' or 'state hook',inorder to get hook go to react .org > docs > using state hook.   

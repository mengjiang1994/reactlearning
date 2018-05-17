//This is my personal React study note
//Reference: http://www.ruanyifeng.com/blog/2015/03/react.html
//Quickly review above blog can help you qucikly review all things


//Demo1
the demo1 shows the basic structure of render(html,js);

I personally recommend use document.querySelector() to replace getElementById()

ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('example')
);

//Demo2
the structure in the render is actually the <html> hirerachy

A view from Full_Stack class:
ReactDOM.render(
	<h1>Hello, React!</h1>,       				//what
	document.querySelector(".information")		//where
)

//demo4
the method React.createClass can creae a component
the initial have to be captical, or you will get error

//demo7
bit of cannot understand..

//demo8





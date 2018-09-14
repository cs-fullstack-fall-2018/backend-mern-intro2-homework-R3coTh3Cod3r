# Backend-mern-intro2-homework

What this YouTube video and comment below what you learned: https://youtu.be/R54neaLznFA

I learned that the client  package json side is seperate from the server package side.
"Axious.get()" is another term use as fetch to local host but "proxy" is use for the local host so it can identify the server.
Smooth techinque to called the client in the "server" would include: ("client": npm start --prefix client"
Concurrently can be use to called the frontend and backend server
To setup the react you need to "npm bootstrap reactstrap uuid react-transiton-group" bootstrap allow use the bootstrap.css etc and reactstrap use bootstrap component as reactstrap component.(should not be in server side)
In "reactstrap" there is  a toggle function which above shows a this.state known as isOpen: refer as "the hamburger menu" meaning when  a responsive Navbar to shows all the links.
Within the Navbar javascript after setting up your constuctor and props you need to implement the code "this.toggle = this.toggle.bind(this); which is use beacuse like render() "this" being identified in the component of the Navbar because toggle is a custom method(code style I use to fit my code) "this" is not included in the code.
We also have the NavBar tags in the render after putting the div inside first and the NavbarToggler is the refer tothe hamburger menu which you want to call the toggle function with a onClick={this.toggle}/>

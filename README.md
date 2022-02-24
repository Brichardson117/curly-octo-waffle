# curly-octo-waffle
This challenge I was tasked to change the code that was used to build the Horiseon website to sematic HTML. 
Starting from the top of the page i changed the <title> inside the <head>. It was originally "website" but I changed it to the company's name "Horiseon" which seems to me more accurate
I changed the first div inside the body to header to more accuratly represent what this section of the code purpose is. Within that section I change the div surronding the <ul> and <A> elements with <nav> since since those elements once clicked on by those viewing their webiste will navigate them to a different section within the webiste.
continuing on to what I labled and the "what we do section" within my html I left one of the <div> elements in and followed it with a <section> and within that section i changes those <div> to <article> which I felt better represent the content in this section. so each section that the <nav> section would redirect the webiste viewwers to were contained inside the own <article>.
the serach engine optimization section was missing an id that was causing a bug tha the redirections from the <nav> section to not working. that was added inside the opening <article> tag for this section
Following that sections for what i labled as Benefits, I added the <aside> element for the content that appears on the right of the web page instead of going in and using <article> element.
Then finally i change the <div> element at the end to <footer> because the <div> was functioning as a footer so it was most logical to change it to <footer>

Small changes did have to be made in the css file do the changes in html but all still functions accoridingly.
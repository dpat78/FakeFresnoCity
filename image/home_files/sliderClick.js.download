
console.log("here is the script");
document.addEventListener("DOMContentLoaded", function(event){
	console.log("DOM is fully loaded");

	var myLink = document.querySelector('#imgLink');
	var target = document.querySelector('#imgSlide');
	var mySrc = "";
	console.log("myLink: ", myLink);
	console.log("target: ", target);


	

	var MutationObserver = window.MutationObserver || window.WebKitMutationObserver || window.MozMutationObserver;
	console.log(MutationObserver);

	var observer = new MutationObserver(function (mutations) {
		console.log("in callback");
	    mutations.forEach(function(mutation) {

	        var entry = {
	          mutation: mutation.target.src
	          
	        }
        	console.log('Recording mutation:', entry);


	         myLink = document.querySelector('#imgLink');
			 console.log("A change was made");
			 switch(mutation.target.src){
			 	 case "http://www.fresnocitycollege.edu/ftp/home_rotation/0.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3348";
			          break;
			     case "http://www.fresnocitycollege.edu/ftp/home_rotation/1.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3338";
			          break;
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/2.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3339";
			          break;
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/3.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3340";
			          break;
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/4.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3341";
			          break;	
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/5.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3342";
			          break;
		      	  case "http://www.fresnocitycollege.edu/ftp/home_rotation/6.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3343";
			          break;		
		      	  case "http://www.fresnocitycollege.edu/ftp/home_rotation/7.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3344";
			          break;	
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/8.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3345";
			          break;
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/9.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3346";
			          break;
			      case "http://www.fresnocitycollege.edu/ftp/home_rotation/10.jpg":
			          myLink.href = "http://www.fresnocitycollege.edu/index.aspx?page=3347";
			          break;
			 };	



	    });
	    
	 });

	

    
    	

	

	console.log("observer: ", observer);

	observer.observe(target, { 'attributes': true, 'attributeFilter': ['src']});


	/* *imgLink.addEventListener('click', function(e){
	   

		
	});  */

});  /* End of document load */


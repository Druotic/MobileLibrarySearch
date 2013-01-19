MobileLibrarySearch
==========================

        Mobile Library Search is a NCSU mobile web that allows the user to search and get the 
		basic information of the current books and media in the library's inventory. Our task 
		is to improve the mobile interface for searching the library's catalog to support a "faceted" 
		search, essentially menu-driven refined search. 
		
        Basically, this is an mobile web, very similar to a web app. This mobile web allows user 
		searching the library database and display the results. Everytime user performs a search, 
		there is an API call that is sent to the live search service. The live search service accepts
		a query string and returns a XML file that contains the results information. The mobile web will
		process the XML file and display results to the user.
		
        For this project, we added lots of functionality to the origin code: adding refine search, 
		changing interface and layout, correcting some limitations, and adding additional option for
		user's conveniences.
		
        Generally, we finished the initial plan to improve this mobile web.
        However there are things that could be improved in future: quick option performing an 
		"on-the-fly search"; adding greater compatibility with a wider range of devices and browsers; 
		display only a few of the sub-filter options while giving the option to expand the list further; 
		optimize choice of provided filter list.
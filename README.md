# hackorsnooze
1. Bootstrap + jQuery libraries 
2. Divide into four sections 
	- navbar with submit/fav>all/brand links
		-navbar submit toggles submit form
		-fav/all toggle??
		
			-fav/all display diff filtered/unfiltered articles
				-all is organized list
				-fav is not organized

			-submit form with "title" + "url" inputs
				- need url validation for url input
				- need to only display hostname input: http://www.google.co.uk >>> (google.co.uk)
					-active link in parenthesis
					- title active link to article
					- SUPER BONUS: hostname filters articles of same hostname 

				- add numbered list item
				- add star icon
					-star needs to toggle from line to solid
					-star 
				-gets class of hostname

			- submit button should add form input to body 
				-should clear form
				- hide form
				-can't reload page / preventDefault 

3. Deploy
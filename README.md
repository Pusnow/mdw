# mdw
My Markdown Wordprocessor

	function mdw(){
		git clone https://github.com/Pusnow/mdw.git "$1"
		cd "$1"
		git remote rename origin update
		git branch --unset-upstream
	}

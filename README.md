# mdw
My Markdown Wordprocessor

	function mdw2(){
		git init "$1"
		cd "$1"
		git submodule add https://github.com/Pusnow/mdw.git .mdw
		cp .mdw/.gitignore .
		git add -A
		git commit -m "Init MDW"
	}

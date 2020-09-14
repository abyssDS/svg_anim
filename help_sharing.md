git add . all the files from my local repository
git commit -m "message here" to add messages to my commits.
git push origin master to upload my files to Github.
git push heroku master to upload my files to Heroku

**Verify remote name/address**
	$git remote -v

	$git push origin master

	$git push myOrigin master

**Remove the old remote**
	$git remote remove myOrigin

**Add missing remote**
	$git remote add origin ssh://git@example.com:1234/myRepo.git
	$git remote add origin <"clone">
		*#clone = "copying https clone URL"*

	$git push origin master


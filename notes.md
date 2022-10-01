## Git notes 
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/D5mit/code_notes.git
- git push -u origin main
- git pull / git pull origin main
- git merge comments 

## Linux notes
- man
- mkdir winter summer
- to run scripts: ./yourscript.sh
- ls -l
- mkdir -p winter/seeds/lettuce (will create alldir, also seeds)
- cd / or cd ~
- touch (used to create blank file or create timestamp)
- rm carrot cat dog
- rm -v carrot cat dog (verbose, means shows what it is doing)
- open . (opens the current directoty) / open purple.txt (will open in desktop)
- mv filenamecurrent filenamenew
- mv filenamecurrnet ~/Desktop
- mv folder/ folder/
- cp -r folder ~/Desktop
- head filename.txt (shows first 10 lines)
- tail -f filaname (continuesly shows last 10 lines)
- date > current_date.txt 
- date >> list_of_dates.txt
- cat file1 file2 file3 > everything.txt
- echo "hello" >> notes.md
- wc notes.md (wordcount)
- cat file1 file2 | wc
- diff -y file1.txt file2.txt
- find . -name '*.md' (find files and sub directory files with .md) 
- grep google file1.txt (will search google in file1.txt)
- grep -r "google" . (search google in all files)
- du -h | sort -h (du is for file size, this looks for largerstr files)
- df -h ~/Desktop/ (shows filesystem of the dir)
- history (nice for showing commands history)
- history (gives a command number to rin it do: !123)
- history | grep "mkdir" (Check history for mkdir)
- ps aux | grep "python" (list processes with a grep pipe)
- top (show top usage in processes)
- kill -15 1234 (not that brutal kill)
- kill -9 1234 (brutal kill)
- jobs (shows jobs)
- bg 1 (run in background, 1 = jobnr)
- fg 1 (run in foreground, 1 = jobnr)
- gzip notes2.md (zip file)
- gunzip notes2.md.gz (zip file)
- gzip -kv notes2.md (zip file, keep file and verbose)
- gunzip -kv notes2.md.gz (unzip file, keep file verbose)
- tar -cf notes23.tar  notes2.md notes3.md (combine files into one)
- tar -xf notes23.tar (uncombine files)
- tar -czf notescombined23.tar.gz notes2.md notes3.md (tar and gzip)
- tar -tf notescombined23.tar.gz (view files in tar file)
- tar -xf notescombined23.tar.gz (extract tar and unzip)
- edit the file: "~/.bashrc" to add permanent aliases
- cat deadplayers.txt | xargs rm -v (creates input for rm)
- who (shows who is logged on)
- su nicola (switch to user)
- sudo chown d5mit readme.txt (change owner)
- cmmod a+r text.txt (u-user, g-group, a-all / rwx)
- pip freeze -> shows all packages installes
- openssl des3 < youfile.txt > yourfile.txt.des3 (to encrypt)
- openssl des3 -d < yourfile.txt.des3 > yourfile.txt.decrypted (to decript)
- hostname -I (gives you the IP address)

## Docker notes
- Docker has an image and a container.  The containers runs only when needed
- sudo dockerd (to start docker)
- sudo docker run docker/whalesay cowsay Hello-World! (run hello world https://hub.docker.com/r/docker/whalesay)
- sudo docker run -d ubuntu sleep 5 (runs docker container in background)
- sudo docker ps -a (see all containers)
- sudo docker rm <container name>  (remove container)
- sudo docker images (to see docker images)
- sudo docker rmi <image name> (removes docker image)
- sudo docker pull <image> (pulls the ubuntu image and stores)

- sudo docker attach a20af (bring docker background to foreground


## AWS Platform training
- IAM - accesss management 






































)

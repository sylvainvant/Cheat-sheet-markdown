# Terminal

ls = list
 * -a = show hidden files
 * -l = detail files
 * -r = recursive

cp = copy
 * -f = force
 * -r = recursive
 * -u = copy if SOURCE file is newer than the destination
 * -a = keeps the same rights

mv = move
 * -backup = make a backup of each existing destination file 
 * -u = move if SOURCE file is newer than the destination

rm = remove
 * -r = recursive
 * -f = force
 * -d remove empty directories -p Deletes parent directories if they become empty

mk = make
 * dir = make directory
 * -p = creates parent directories if they dont exist

cd = change directory
 * *-* = return last dir
 * .. = parent file
 * ... = parent of parent file..

ln = link
 * -s = symbolic
 * -f = force and overwrites if it exits
 * -d = link on directory ( only in root )

find (natif recursive)
 * -(i)name = search by name (i for indifferent to the casse)
 * -type = search by type
 * -link = searching for the number of links to the file
 * -exec = executes the command given to the found files

man = manual

pwd = print working directory

grep = Searches for a character string in files 

cat = concatenate

chmod = change mode

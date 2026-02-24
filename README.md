# shell00
This is the first C Piscine

# to be used at the evaluation
go to home -> evaluation and run in terminal <br>
git clone * name <br>
tar -xvf testShell00.tar <br>
tar -xvf exo2.tar <br>
ls -l <br>
bash git_commit.sh | cat -e <br>
bash git_ignore.sh | cat -e (run on root folder) <br>
copy a and sw_org.diff <br>
diff a b > sw.diff <br>
touch "\~" "a~" "~b" "#c#" "#d" "#e" <br>
file -m ft_magic test_file <br>

# the commands I used so far
create a file -> touch <br>
create a directory -> mkdir <br>
change time of a file or directory -> touch -t 06012342 testShell00 <br>
change time of a symbolic link -> touch -d "2026-06-01 22:20" test6 <br>
change permmisions -> chmod wrxwrxwrx (777) <br>
list all files with entries with long listing format -> ls -la <br>
ssh-keygen -> generate keygen <br>
rm 'file' -> remove file <br>
rm -r 'folder' -> remove folder <br>
git clone git@vogsphere.42heilbronn.de:vogsphere/intra-uuid-edf1da62-6cea-43c5-b1f8-5b59236df212-7271697-ecakiray sh00 -> clone the remote repo to sh00 folder <br>
vim -> edit file <br>
cat -> print file <br>
git add . -> add all files <br>
git status -> show status <br>
git config --global --edit -> edit username, etc. <br>
git push -> push the commit <br>
klist -> list the session <br>
kinit ecakiray -> init the session <br>
ln test3 test5 -> hard link <br>
ln -s test0 test6 -> soft link <br>
touch -d "2026-06-01 21:46" test1 -> change date of a file <br>
touch -h -t 202501062220 test6 -> change date of a symbolic link <br>
ls -ltp | tr '\n' ', ' -> list files (l is for long format, t is sorting by time, p is adding \ to the end of the file and tr is for translating from one to another <br>
ls -mtp (is a better option for first one) <br>
git log -n 5 --format=%H -> display the last 5 git commits and display only the commit hashes <br>
git ls-files --others -i --exclude-standard -> list files others (others mean not tracked, i means ignored exclude standart means standard ignore rules) <br>
find . -type f \( -name '*~' -o -name '#*#' \) -print -delete -> find files in the directory and the all subdirectories, starting with ~ or starting and ending with #, then apply print first and than delete <br>
